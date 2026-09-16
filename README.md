# kaicryan.dev

Personal portfolio site for Kai Cryan — web development & infrastructure.

**Live:** [kaicryan.dev](https://kaicryan.dev)

## About

A single-page portfolio built around real project case studies — including
a freelance e-commerce build ([CODE369](https://kaicryan.dev/projects/code369.html))
and a self-hosted home lab ([Home Lab](https://kaicryan.dev/projects/home-lab.html))
— written to broaden full-stack skills deliberately rather than lean on a
template.

## Tech stack

- Vanilla HTML / CSS / JavaScript — no framework, no build step
- Canvas-based animated background (a drifting "signal/network" node field)
- Self-hosted, served from a home Docker/Linux server

## Structure

```
.
├── index.html              # Main page (about, approach, process, projects, contact)
├── projects/
│   ├── code369.html         # Case study: freelance e-commerce build
│   └── home-lab.html        # Case study: self-hosted home lab
└── assets/
    └── images/               # Screenshots, favicons, spec docs
```

## Running locally

No build step — just serve the directory:

```bash
git clone https://github.com/KaiCryan/kaicryan.dev.git
cd kaicryan.dev
python3 -m http.server 8000
# open http://localhost:8000
```

## License

All rights reserved — this is a personal portfolio; the code is here for
transparency and reference, not reuse.
