# python42

> The current answers for Python, the universe, and everything.

This project and its README document my *current* view on the Python eco-system, and specifically how to create, maintain, and release Python projects. And yes, this changes over time which is quite natural, driven by the PEP process and evolving tools.

It reflects *my* preferences and choices, YMMV. Whenever possible, I'll try to provide enough background regarding those choices via some linked resources, which usually explain things better than I could here. This page is intended to be and remain a reasonably short document.


🚧 🐉🐉🐉 HERE BE DRAGONS! 🐉🐉🐉

Basic development environment on the three major platforms:
 * Generally, some kind of POSIX environment; it makes things easier if you can assume a 'normal' shell being in reach.
 * *Linux*: bash or some other shell, the usual.
 * *MacOS*: The BSDish environment that you get from using [Homebrew](https://brew.sh).
 * *Windows*: Preferably WSL2 and some Linux distro (Ubuntu LTS by default); 'git bash' (MingW) if you must, but there might be some pain.
 * *VS Code* as an editor and IDE (other options include: PyCharm, Spider, Jupyter, ...).

Project tooling:
 * pdm
 * duty
 * copier

CI / CD:
 * GitLab or GitHub
 * docker / OCI containers (details!)

QA / Security:
 * flake8
 * ruff?

Documentation:
 * A single README for small projects (little tools)
 * Sphinx otherwise
 * Maybe mkdoc for something 'in the middle'
