# louridoc.github.io

Personal website of Christian Lourido: robotics software engineer (motion planning and AI-driven perception) with a Ph.D. in Mechanical Engineering from NYU Tandon.

Live site: https://louridoc.github.io

Built with Jekyll on the [AcademicPages](https://github.com/academicpages/academicpages.github.io) template (a fork of Minimal Mistakes).

## Content

| What | Where |
|---|---|
| About page | `_pages/about.md` |
| Work experience (also feeds the CV page) | `_teaching/` (published at `/experience/`) |
| Publications | `_publications/` |
| Projects | `_projects/` |
| CV page | `_pages/cv.md` |
| CV PDF | `assets/Christian_Lourido_CV.pdf` (built from the LaTeX CV, `cv.tex`) |
| Site settings, sidebar | `_config.yml` |
| Header links | `_data/navigation.yml` |

Videos are hosted on YouTube; `media/` and video files are git-ignored.

## Local preview

Requires Ruby 3.3 (the version GitHub Pages uses).

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
