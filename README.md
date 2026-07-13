# Personal site

This is a small Jekyll site using the upstream [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) theme.

## Local preview

```bash
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve --host 127.0.0.1 --port 4000
```

Then open `http://127.0.0.1:4000/`.

## Writing

Add blog posts under `_posts/` with a filename like `2026-07-13-my-note.md`.

## Reading tracker

Add papers and books to `_data/reading.yml`; they render at `/reading/`.
