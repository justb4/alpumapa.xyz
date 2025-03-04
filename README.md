# alpumapa.xyz website

The files and dirs below are content for an OpenStreetMap Workshop.

This workshop was initially provided at the [FOSS4GNL 2023](https://foss4g.nl) and expanded 
for workshops in Alpujarra, Spain.

The documentation is powered by [MkDocs](https://www.mkdocs.org) 
which facilitates easy management
of content and publishing. Content is written in Markdown.

Using [GitHub Workflows](.github/workflows/deploy.docs.yml) the website is automatically rebuilt and deployed
(to the `gh-pages` branch on GitHub) on commit/pushes to the `main` branch. 
The site is hosted as a static html website at [alpumapa.xyz](https://alpumapa.xyz) 
on GitHub using GitHub Pages.

## Build/test locally

```bash
# build a virtual Python environment in isolation
# For example, or use pyenv.
python3 -m venv .
. bin/activate

# fork or clone from GitHub
git clone https://github.com/justb4/alpumapa.xyz.git
cd docs

# install required dependencies

# Optional: install lxml quickly using package
apt-get install -y python3-lxml

# install Python libs 
pip install -r requirements.txt

# build the website
mkdocs build

# serve locally
mkdocs serve  # website is made available on http://localhost:8000

# or locally on specific port
mkdocs serve -a localhost:8001

```

## Deploying to live site

Website updates are automatically published 
via [GitHub Actions](.github/workflows/deploy.docs.yml).

Or to publish manually, but this is in general not needed:

```bash
# NOTE: you require access privileges to the GitHub repository
# to publish live updates
mkdocs gh-deploy -m 'add new page on topic x'
```