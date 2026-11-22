# Mahi Aminu Aliyu: personal website

Source for [a-l-mahi.github.io](https://a-l-mahi.github.io), built with Jekyll and the [al-folio](https://github.com/alshedivat/al-folio) theme.

## Where things live

| What              | File                                                                         |
| ----------------- | ---------------------------------------------------------------------------- |
| About / bio       | `_pages/about.md`                                                            |
| Publications      | `_bibliography/papers.bib` (`selected={true}` puts a paper on the home page) |
| News              | `_news/announcement_*.md`                                                    |
| CV                | `assets/pdf/Mahi_Aminu_Aliyu_CV.pdf` (replace the file, keep the name)       |
| Other shared PDFs | `assets/pdf/` → served at `https://a-l-mahi.github.io/assets/pdf/<file>`     |
| Site settings     | `_config.yml`                                                                |

## Preview locally

```bash
docker compose up        # then open http://localhost:8080
```

or, with Ruby and Bundler installed: `bundle install && bundle exec jekyll serve`.

Pushing to `master` deploys the site through GitHub Actions (`.github/workflows/deploy.yml`) to the `gh-pages` branch.
