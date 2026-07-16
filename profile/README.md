# CatalogueCanvas

CatalogueCanvas is a self-hosted catalogue server. You upload ZIP files containing your work, organize them into collections, add metadata and descriptions, and share curated portfolios as shareable pages.

Unlike a repository or organized folder structure, CatalogueCanvas treats your work as FAIR data: **Findable** through search and tagging, **Accessible** with metadata and preview generation, **Interoperable** across formats and libraries, and **Reusable** through portfolios and structured metadata.

## What's here

- **[Documentation](https://cataloguecanvas.app/)** 
- **[Demo](https://cataloguecanvas.app/demo/)**

This organization contains the source code and documentation for CatalogueCanvas:

- **[CatalogueCanvas](https://github.com/ToroRojo-code/CatalogueCanvas)** — the application
- **[cataloguecanvas-website](https://github.com/ToroRojo-code/cataloguecanvas-website)** — documentation and showcase site
- **[cataloguecanvas-homeassistant-addon](https://github.com/CatalogueCanvas/cataloguecanvas-homeassistant-addon)** — Home Assistant add-on

## Features

- **Ingest** — upload ZIP files as items; images convert to WebP previews automatically
- **Organize** — group items into collections, mark favorites, search
- **Annotate** — edit titles, tags, notes; use a local vision model to generate descriptions
- **Publish** — create portfolios and share them at `/p/<slug>` links
- **Store** — back up the database and all files; use multiple storage libraries

## Who uses it

Digital artists cataloguing a body of work and publishing portfolios. Generative coders keeping rendered images and source code in the same item. Designers organizing asset sets. Studios and self-hosters running a catalogue on their own hardware.

## Installation

Docker is the easiest way to run it, even on a low-powered machine. Bare-metal installs also work on Linux, macOS, and Windows, but you'll need Python 3.11+, Node.js 22+, and `uv`.

See the [full installation guide](https://cataloguecanvas.app/documentation/install/) for details.


## License

GNU Affero General Public License v3.0
