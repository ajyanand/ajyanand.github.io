# ajyanand.github.io

Personal academic portfolio for Ajay Anand, built as a GitHub Pages static site.

## Structure

- `_data/profile.yml` holds core bio, contact, social, research, and resume links.
- `_data/publications.yml` holds selected publications and project links.
- `_data/instagram.yml` holds the photography Instagram integration.
- `media/resume/Ajay_Anand_Resume.pdf` is the reserved path for the current resume PDF.

## Local development

GitHub Pages builds this with Jekyll. For local development, install Ruby tooling and run:

```bash
bundle install
bundle exec jekyll serve
```

The site is designed to stay static-hosting friendly and can be migrated to Hugo later because the content is already separated from the presentation.
