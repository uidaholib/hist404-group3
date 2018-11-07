# History 404 Class Instructions:

1. Download your group’s metadata spreadsheet as a csv (comma separated values) file from google sheets (https://docs.google.com/spreadsheets/d/10I2Z9-pfD3s4dOZQJlmO6mU64uWKnCvZUdO-JUCC2-I/edit#gid=0):
    - Go to File -- Download as -- Comma-separated values (.csv, current sheet)

2. Without opening the file, rename it as metadata.csv

3. Upload metadata.csv to the _data folder in your group’s Github repository

4. At this point, the librarian working with your group will show you how to preview the digital collection

5. Were there mistakes in your collection’s display? If so, return to your group’s metadata spreadsheet and correct any metadata mistakes **(Note: please make any edits only to your group's metadata sheet, not the class sheet)**
    - Hints: 
        - Make sure the filename in your metadata matches the file's name in reality.
        - Did you add .jpg or .pdf to the end of your filename?
        - Make sure your date is in the proper date format (yyyy-mm-dd).
        - Are your latitude and longitude entered in the correct columns?

6. Repeat steps 1-4, replacing the metadata.csv file with the most recently updated version of your metadata

7. When your exhibit is displaying properly, proceed to changing the content and look of your site:
    - _config.yml
      - Change site title, description, and theme
    - index.md
      - Change banner image, featured subjects, and featured places
    - about.md
      - Change featured image, about page content


# About the site you're using: collectionbuilder-gh

https://github.com/CollectionBuilder/collectionbuilder-gh

> **work in progress!**

A project to generate a free and simple digital collection site using [GitHub Pages](https://pages.github.com/) given:

- a CSV of collection metadata
- a folder of JPEG images or PDF documents

See [Getting Started Docs](docs/index.md) for detailed information.

`collectionbuilder-gh` is intended as a simple template for hands-on teaching about digital libraries.
It can be used in a workshop setting to take participants through digitization and metadata creation, to having a live collection site hosted on GitHub.

Similar learning experiences use [Omeka](https://omeka.org/) or other DAMS/[CMS](https://en.wikipedia.org/wiki/Content_management_system) platforms that are overkill for one off projects.
Although CMS feature familiar GUI administration interfaces, they are not simple to learn and customize.
These experiences must focus on teaching the specific tool rather than general web skills and the heavy infrastructure is a barrier to adoption and further development.

`collectionbuilder-gh` aims to be well documented and easy to configure by following the example, with the potential to scaffold to learn a multitude of transferable digital and data skills.
A project in "minimal computing", it provides a depth of learning opportunities, allowing users to take complete ownership over the project and make their work open to the world.

Learn about:

- Git and GitHub basics
- [Markdown](https://guides.github.com/features/mastering-markdown/), plaintext writing and content creation
- HTML, CSS, and JS literacy
- commandline literacy
- GitHub collaboration and project management
- [Jekyll](https://jekyllrb.com/) basics
- working in the Open, open source and open data
- digital libraries concepts such as "collections as data", minimal computing, data-driven design

**Note:** 
Since `collectionbuilder-gh` uses [GitHub Pages](https://pages.github.com/), it is only suitable for small collections, with lower resolution images.
GitHub repositories are limited to 1GB.

> We prefer commonly understood formats (such as CSV spreadsheets over YAML), and convention over configuration (follow the example over learn all the options).

## Features

- [Jekyll](https://jekyllrb.com/) for GitHub Pages 
- Layout using [Bootstrap](https://getbootstrap.com/docs/4.0/getting-started/introduction/).
- [jQuery](https://jquery.com/)
- Mapping using [Leaflet.js](http://leafletjs.com/)
- Tables using [DataTables](https://datatables.net/)
- Galleries using [lightGallery](http://sachinchoolur.github.io/lightGallery/)
- Simple [lunr](https://lunrjs.com/) search 
- Rich markup using [Schema.org](http://schema.org) and [Open Graph protocol](http://ogp.me/) standards.

## Build a Digital Collection! 

Check out the [Docs](docs/index.md).
