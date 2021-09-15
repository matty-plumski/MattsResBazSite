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
 Matt Plummer, Victoria University of Wellington


---

## WHAT?

- Free, static, git-based websites - maintainable and version-controlled
- Based on open source Hugo theme (Academic)
- Packaged by Wowchemy, deployed by Netlify
- Markdown-based, supports math equations, code-highlighting and diagrams
- Also CSS, HTML, Shortcodes, Front Matter, Config files (yml, toml)

<section>
![image](/media/concept_map.png)
</section>

---

## WHY?

- Intrinsic motivation - website design is fun, academic portfolio site useful for research engagement. 
- Low risk, free-to-fail sandpit
- Excellent way to teach version control - benefits and processes
- Encourages troubleshooting - deploy logs, community fora
- Helps build a community of practice around a common, richly-tooled ecosystem
- Entry-level training that creates a platform for collaboration and further capability development
- Immediacy - live site deployed and first git commit made within minutes

<section>
<section>
{{< video library="true" src="Deploy_video.mp4" controls="yes" >}}
</section>
  <section><iframe width="560" height="315" src="https://www.youtube.com/embed/5vfZCbbpNus" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</section>
</section>
  <section>
  ![image](/media/netlify_git.png)
</section>
</section>

---

## HOW?

- Carpentries-inspired methodology - sticky notes + formative feedback
- Code-along approach, with clear explanations 
- Help - ratio of instructor to attendees, or supplemented with a helper
- Different levels of skill and experience accommodated
- Peer support
- Repetition and modular, scaffolded approach 
- Paper-based handouts of key information (concept map of components, directory structure of site, Markdown cheat sheet)

---

## FUTURE PLANS

- Carpentries-inspired methodology - sticky notes + formative feedback
- Code-along approach, with clear explanations 
- Help - ratio of instructor to attendees, or supplemented with a helper
- Different levels of skill and experience accommodated
- Peer support
- Repetition and modular, scaffolded approach 
- Paper-based handouts of key information (concept map of components, directory structure of site, Markdown cheat sheet)

---

### CONTACT

matt.plummer@vuw.ac.nz


```
{{%/* fragment */%}} One {{%/* /fragment */%}}
{{%/* fragment */%}} **Two** {{%/* /fragment */%}}
{{%/* fragment */%}} Three {{%/* /fragment */%}}
```

Press `Space` to play!


{{% fragment %}} **Two** {{% /fragment %}}
{{% fragment %}} Three {{% /fragment %}}

---


---

### WORKSHOP FEEDBACK

- Great workshop - very interesting and easy to follow (and fun!). Found it very worthwhile
- Perfect step-by-step instructions / learning by doing approach, really helpful
- The session has been really informative and useful. I've learnt heaps. Can't wait for the next session. Thanks, Matt!!
- I learned it for the first time. Thank you. It was helpful.
- Great pace, great explanation, very well prepared. I fell empowered and really enjoyed this. Thank you!!
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
