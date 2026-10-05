# Kaiden Pollesch Portfolio V2 (Hugo)

Static site, no JavaScript. Needs Hugo 0.123 or newer. Everything is available as soon as a page loads.

## Run locally
```bash
hugo server
```

## Editing

| What                                             | Where                                                    |
|--------------------------------------------------|----------------------------------------------------------|
| Name, tagline, footer snippet, links, nav labels | `hugo.toml`                                              |
| About and Expertise text                         | `content/about/_index.md`, `content/expertise/_index.md` |
| Welcome page text                                | `content/_index.md`                                      |
| Email,  LinkedIn, and Resume message             | `content/contact/_index.md`                              |
| Colors and font                                  | variables at the top of `static/css/style.css`           |

Links to other sites (http, https, mailto) are styled in the red link color automatically. Internal links use the text color.

## Add a project
```bash
hugo new content projects/my-project.md
```
Set `category` to `school` or `personal`, plus `tldr` and `tech`. Set `date` to when it started; newest shows first.

## Add experience or education
```bash
hugo new content experience/my-job.md
```
Set `type` to `employment` or `education`, `date` (start) and `end`. Newest shows first.

## Deployment

The site deploys to `kaidenpollesch.com` my domain through GitHub Pages through GitHub Actions on every push to `main`, using `.github/workflows/hugo.yml`.

## Credit

Design Layout and tone inspired by [lucianonooijen.com](https://lucianonooijen.com/). All code and content here are written separately.
