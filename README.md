# wdianrdk.github.io

The source repository for [Yung-Jung Cheng's personal academic website](https://wdianrdk.github.io/).

The site uses **GitHub Pages**, **Jekyll**, and the **Minima** theme. Its content is written mainly in Markdown; no separate frontend application is required.

## Pages

| Source file | Page |
| --- | --- |
| `index.md` | Home |
| `About me.md` | About Me (`/about/`) |
| `Research.md` | Research |
| `Projects.md` | Projects |
| `MFS.md` | Map, Food, Smile |
| `contact.md` | Contact |

## Updating the site

1. Edit the Markdown file for the relevant page.
2. Keep the YAML front matter at the top of each page.
3. When changing the navigation, edit `header_pages` in `_config.yml`. The paths must match the source filenames, including capitalization and spaces.
4. Review the changes in a pull request before merging into `main`.

Images used by the MFS page live in `image/`. Public research links should point only to materials intended for public release.

## Local preview

If you have a compatible Jekyll environment installed, you can preview the site with `bundle exec jekyll serve` after setting up the required gems. Otherwise, edit the Markdown directly on GitHub and let GitHub Pages build the site after merging.
