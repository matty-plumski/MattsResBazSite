---
title: Static Tactics
summary: Using static website workshops to develop capability and collaboration.
authors: [admin]
tags: [open source, research impact, skill development, code, training]
categories: [skill development]
date: "2021-09-15T00:00:00Z"
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: night
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

### STATIC TACTICS
#### Using static website workshops to develop capability and collaboration.
#### Matt Plummer, Victoria University of Wellington


---

## WHAT?

- Static, git-based websites - maintainable and version-controlled
- Based on Hugo theme (Academic)  
- Packaged by Wowchemy, deployed by Netlify
- Markdown-based, support math equations, code-highlighting and diagrams
- Also CSS, HTML, Shortcodes, Front Matter, Config files (yml, toml)


---

## WHY?
<section>
- Intrinsic motivation - website design is fun, academic portfolio site useful for research engagement. 
- Low risk, free-to-fail sandpit
- Excellent way to teach version control - benefits and processes
- 
- Overview: `Esc`
- Speaker notes: `S`
- Fullscreen: `F`
- Zoom: `Alt + Click`
- Teaches Troubleshooting
- Helps build a community of practice around a common, richly-tooled ecosystem
- Immediacy - live site deployed and first git commit made within minutes
</section>

<section>
<section>
{{< video library="true" src="Deploy_video.mp4" controls="yes" >}}
</section>
  <section>Vertical Slide 2</section>
</section>

---

## HOW?

- Carpentries-inspired methodology - sticky notes + formative feedback
- Code-along approach, with clear 
- Help - ratio of instructor to attendees, or supplemented with a helper
- Different levels of skill and experience accommodated
- Peer support
- Repetition and modular, scaffolded approach 
- Speaker notes: `S`
- Fullscreen: `F`
- Zoom: `Alt + Click`
- Paper-based handouts of key information (concept map of components, directory structure of site, Markdown cheat sheet)

---

## Mat

In-line math: $x + y = z$

Block math:

$$
f\left( x \right) = \;\frac{{2\left( {x + 4} \right)\left( {x - 4} \right)}}{{\left( {x + 4} \right)\left( {x + 1} \right)}}
$$

---

## Fragments

Make content appear incrementally

```
{{%/* fragment */%}} One {{%/* /fragment */%}}
{{%/* fragment */%}} **Two** {{%/* /fragment */%}}
{{%/* fragment */%}} Three {{%/* /fragment */%}}
```

Press `Space` to play!


{{% fragment %}} **Two** {{% /fragment %}}
{{% fragment %}} Three {{% /fragment %}}

---

A fragment can accept two optional parameters:

- `class`: use a custom style (requires definition in custom CSS)
- `weight`: sets the order in which a fragment appears

---
```markdown
classDiagram
    GitHub --|> Personal Computer : Pull 
    GitHub <|-- Personal Computer : Push 
    Personal Computer <|-- GitHub Desktop
    Personal Computer <|-- Command Line
    GitHubDesktop <|-- TextEditor
    Command Line <|-- TextEditor
    GitHubDesktop <|-- File Explorer
    Command Line <|-- File Explorer
    

    Website --|> Slides
    Website --|> Blogs
    Website --|> Projects
    Website --|> CV
    Website --|> Publications
    GitHub : web-based
    GitHub : version controlled
    GitHub : collaboration tool
  

   GitHub --|> Website : Deploy(netlify.com)

    class Personal Computer{
    }
    class Website{
    }
    class TextEditor{
        Edit markdown
    }
    class FileExplorer{
        Add images 
    }
```markdown  

## Speaker Notes

Add speaker notes to your presentation

```markdown
{{%/* speaker_note */%}}
- Only the speaker can read these notes
- Press `S` key to view
{{%/* /speaker_note */%}}
```

Press the `S` key to view the speaker notes!

{{< speaker_note >}}
- Only the speaker can read these notes
- Press `S` key to view
{{< /speaker_note >}}

---

## Themes

- black: Black background, white text, blue links (default)
- white: White background, black text, blue links
- league: Gray background, white text, blue links
- beige: Beige background, dark text, brown links
- sky: Blue background, thin dark text, blue links

---

- night: Black background, thick white text, orange links
- serif: Cappuccino background, gray text, brown links
- simple: White background, black text, blue links
- solarized: Cream-colored background, dark green text, blue links

---

---
```mermaid
classDiagram
    GitHub --|> Personal Computer : Pull 
    GitHub <|-- Personal Computer : Push 
    Personal Computer <|-- GitHub Desktop
    Personal Computer <|-- Command Line
    GitHubDesktop <|-- TextEditor
    Command Line <|-- TextEditor
    GitHubDesktop <|-- File Explorer
    Command Line <|-- File Explorer
    

    Website --|> Slides
    Website --|> Blogs
    Website --|> Projects
    Website --|> CV
    Website --|> Publications
    GitHub : web-based
    GitHub : version controlled
    GitHub : collaboration tool
  

   GitHub --|> Website : Deploy(netlify.com)

    class Personal Computer{
    }
    class Website{
    }
    class TextEditor{
        Edit markdown
    }
    class FileExplorer{
        Add images 
    }
```  
---

## Themes

- black: Black background, white text, blue links (default)
- white: White background, black text, blue links
- league: Gray background, white text, blue links
- beige: Beige background, dark text, brown links
- sky: Blue background, thin dark text, blue links

---

- night: Black background, thick white text, orange links
- serif: Cappuccino background, gray text, brown links
- simple: White background, black text, blue links
- solarized: Cream-colored background, dark green text, blue links

---

{{< slide background-image="/media/webcode.jpg" >}}

## Custom Slide

Customize the slide style and background

```markdown
{{</* slide background-image="/media/webcode.jpg" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
![image](/media/web_concept.png)
```
![image](/media/web_concept.png)
---

## Custom CSS Example

Let's make headers navy colored.

Create `assets/css/reveal_custom.css` with:

```css
.reveal section h1,
.reveal section h2,
.reveal section h3 {
  color: navy;
}
```

---

# Questions?

[Ask](https://spectrum.chat/academic)

[Documentation](https://sourcethemes.com/academic/docs/managing-content/#create-slides)
