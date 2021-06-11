---
title: Mermaid_test
summary: testOfMermaid
date: "2018-06-28T00:00:00Z"

reading_time: true  #?
share: true  # Show social sharing links?
profile: true  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `static/media/` folder).
header:
  caption: 
  image:
---

{{< mermaid >}}

erDiagram
    RAAPOI-MASTER }|..|{ QUICKTEST : CODE_TESTING_JOBS
    QUICKTEST{
        ITL04n01 
        ITL04n02
        ITL04n03 
        ITL04n04
    }
    QUICKTEST ||--o{ QUICKTEST_INFO : NOTES
    QUICKTEST_INFO{
    maxRuntime fiveHours
    Purpose testSmallJobs
    IP-Range  FourtyFour_FourtySeven
    }
    RAAPOI-MASTER }|..|{ BIG_MEM : HIGH_MEMORY_JOBS
    BIG_MEM{
        HIGH01
        HIGH02
        HIGH03    
        HIGH04
        HIGH05
        HIGH06
    }
    BIG_MEM ||--o{ BIG_MEM_INFO : NOTES
    BIG_MEM_INFO{
    maxRuntime tenDays
    Purpose highMemoryJobs
    }
    RAAPOI-MASTER }|..|{ PARALLEL : GENERAL_PURPOSE_JOBS
    PARALLEL{
        SPJ01
        ITL01n01-4
        ITL02n02-4
        ITL03n03-4
        AMD01n01-4
        AMD02n01-4
        AMD03n01-4
        AMD04n01-4
        AMD05n01-4
        AMD06n01-4
        GPU01
        GPU02    
    }
    PARALLEL ||--o{ PARALLEL_INFO : NOTES
    PARALLEL_INFO{
    maxRuntime tenDays
    Purpose generalPurposeJobs
    SPJ spaceJam
    ITL Intel_node
    AMD AMD_node
    GPU graphicsNode
    }
    RAAPOI-MASTER }|..|{ STORAGE : STORAGE
    STORAGE{
        BEE01 
        BEE02
        BEE03
        RAAPOI_FS01
    }
    STORAGE ||--o{ STORAGE_INFO : NOTES
    STORAGE_INFO{
    BEE beeX_cluster
    FS fastStorage
    FS_Size Two_x_50Terrabytes 
    }
    RAAPOI-MASTER }|..|{ UTILITY : DATA_TRANSFER
    UTILITY{
        DTn01
        DHCP_PXE
    }
    UTILITY ||--o{ UTILITY_INFO : NOTES
    UTILITY_INFO{
    DTn01 dataTransferNode
    Purpose transferLargeFilesToScratchStorage
    DCHP IP_Allocation
    DCHP_Notes staticBasedOnMACAddress
    Location VLAN_1901
    }

    {{< /mermaid >}}