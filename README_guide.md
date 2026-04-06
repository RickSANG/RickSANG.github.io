# Lindi Sang Personal Website Guide

This repository contains the source code for Lindi Sang's academic homepage: [ricksang.github.io](https://ricksang.github.io).

The site is built with Jekyll on top of the Academic Pages theme and is used to present research interests, CV, projects, publications, and contact information.

## Profile Summary

- Name: Lindi Sang (Ricky Sang)
- Current position: M.S. student in Materials Science and Engineering at the National University of Singapore
- Research interests: machine-learning potentials, heterogeneous catalysis, computational materials science, AI-accelerated atomistic modeling
- Contact email: <sld150000@163.com>
- GitHub: [RickSANG](https://github.com/RickSANG)
- CV PDF: `files/SangLindi_CV.pdf`

## Main Content Locations

- Home page introduction: `_pages/about.md`
- Sidebar profile and social links: `_config.yml` and `_includes/author-profile.html`
- Online CV page: `_pages/cv.md`
- Static CV file: `files/SangLindi_CV.pdf`
- Navigation menu: `_data/navigation.yml`

## Current Academic Background

### Education

- M.S. in Materials Science and Engineering, National University of Singapore, 2025.08 - 2026.06 expected
- B.S. in Materials Science and Engineering, University of Electronic Science and Technology of China, 2021.09 - 2025.06

### Research and Work

- AI-accelerated surface catalysis modeling based on GNN and Transformer architectures
- Machine-learning potentials for heterogeneous catalysis
- First-principles simulation and atomistic modeling
- Internship experience at A*STAR IHPC and EVE Energy

### Skills

- Python, MATLAB, Verilog, Linux
- VASP, Nanodcal, fairchem framework
- Magnetron sputtering, UV photolithography, semiconductor device fabrication

## How To Update The Website

1. Edit `_config.yml` for global profile information such as title, description, email, WeChat, Bilibili, and GitHub.
2. Edit `_pages/about.md` to update the homepage self-introduction.
3. Edit `_pages/cv.md` to update the online CV.
4. Replace `files/SangLindi_CV.pdf` when a new PDF CV is available.
5. Commit and push to GitHub to trigger GitHub Pages deployment.

## Run Locally

This project is typically developed in WSL on Windows.

1. Install Ruby, Bundler, and Node.js.
2. Run bundle install.
3. Start the local server with bundle exec jekyll serve -l -H localhost.
4. Open [http://localhost:4000](http://localhost:4000).

If permissions cause gem install issues, run:

```bash
bundle config set --local path 'vendor/bundle'
bundle install
```

## Deployment Notes

- Production site: [ricksang.github.io](https://ricksang.github.io)
- Repository: [RickSANG/RickSANG.github.io](https://github.com/RickSANG/RickSANG.github.io)
- GitHub Pages rebuilds automatically after pushes to the main branch.

## Maintenance Notes

- Remove leftover template text whenever profile information changes.
- Keep the homepage, sidebar, and CV page consistent with the latest CV PDF.
- Prefer updating both the online CV and the PDF together to avoid content drift.
