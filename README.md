# wangechikariuki.github.io

Personal academic website of Wangechi Kariuki, PhD student in Law at the University of Washington School of Law.

Live site: https://wangechikariuki.github.io

Built with [Jekyll](https://jekyllrb.com/) on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template and published by GitHub Pages from the `master` branch.

## Where things live

| What | File |
| --- | --- |
| Home page (About, research interests) | `_pages/about.md` |
| Resume | `_pages/resume.md` |
| Publications list | `_pages/publications.html` |
| Individual publications | `_publications/` (one Markdown file each) |
| Top navigation | `_data/navigation.yml` |
| Name, bio, sidebar links, site description | `_config.yml` |
| Profile photo | `images/profile.png` |

## Adding a publication

Copy the file in `_publications/`, rename it `YYYY-MM-DD-short-title.md`, and update the front matter (`title`, `date`, `venue`, `link`, `citation`).

## Previewing locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
