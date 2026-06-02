# ismty0805.github.io

Personal homepage, built with [Jekyll](https://jekyllrb.com/) and deployed on
GitHub Pages. Based on a fork of
[myungkyuKoo.github.io](https://github.com/myungkyuKoo/myungkyuKoo.github.io),
which itself builds on [Martin Saveski](https://web.media.mit.edu/~msaveski/)'s template.

## Customize your content

| What | Where |
|------|-------|
| Name, title, email, social links, profile photo | `_data/main_info.yaml` |
| Publications list | `_data/publications.yaml` |
| About / Education / Experience / Honors sections | `index.html` |
| Profile photo | `assets/profile-pics/` (update path in `main_info.yaml`) |
| CV PDF | `assets/cv/CV.pdf` |
| Publication teaser images | `assets/publications/<paper>/` |
| Google Analytics | set `google_analystics_tracking_id` in `_data/main_info.yaml` |

## Run locally

```bash
bundle install      # first time only (needs Ruby + Jekyll)
bundle exec jekyll serve
# open http://localhost:4000
```

## Deploy

Push to the `main` branch of the `ismty0805/ismty0805.github.io` repository.
GitHub Pages builds and serves it at https://ismty0805.github.io automatically.
