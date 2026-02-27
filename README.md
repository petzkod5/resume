# Dylan Petzko, Full-Stack / Software Engineer - Resume

Just my resume. But in code cause I'm too lazy to edit a doc file. Also I don't know how to use
Microsoft tools that well... and I like code / html / LaTeX better.

# How to build it

> I use 'uv' for most things - so just install that first

Run Weasyprint on the `resume.html`
```bash
uvx weasyprint resume.html resume.pdf
```

## Changing From Light / Dark

If you open the html file locally - it'll just render a button that'll let you swap between themes.

Before rendering it via weasyprint you'll need to change the default class from "dark" -> "light"

```bash
sed 's/class="dark"/class="light"/' resume.html
```
