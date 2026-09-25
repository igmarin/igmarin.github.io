# Ismael Marin’s GitHub Pages site

[Visit the site](https://igmarin.github.io/) · [Read the résumé](https://igmarin.github.io/resume/) · [See the code](https://github.com/igmarin)

This site connects [Ismael’s main portfolio](https://ismaelmarin.dev/) with his technical work on GitHub. It highlights selected projects, writing, and ways to get in touch.

## Run locally

The site uses plain HTML, CSS, and a little JavaScript. There is no build step or dependency install.

```sh
python3 -m http.server 8000
```

Open [localhost:8000](http://localhost:8000/) from the repository root. Stop the server with `Ctrl-C`.

## Where things live

| Path | Content |
| --- | --- |
| `index.html`, `css/style.css` | Homepage and styles |
| `resume/index.html` | Web résumé |
| `resume/ismael-marin-resume.pdf` | Downloadable CV |
| `resume/llms-resume.txt`, `llms.txt` | Text versions of the résumé and site overview |
| `*-site/` | Individual project pages |
| `robots.txt`, `sitemap.xml` | Search crawler files |

GitHub Pages publishes the root of `master` at [igmarin.github.io](https://igmarin.github.io/). Changes to the résumé or career claims should stay consistent across the HTML, text, and PDF versions. See [AGENTS.md](AGENTS.md) for the editing guide.
