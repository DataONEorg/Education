# Guidelines for contributors and content editors

The lessons are generated from markdown documents. These guidelines will walk
you through the repository organization, the markdown basics, and any additional
information.

## Repository organization

Every lesson is a single folder within the `lessons` directory. Each lesson
folder is called `XX_keyword`, where `XX` is the lesson number, and `keyword` is
a brief description of the lesson. The slides themselves are in a file called
`index.md`. Do not use another filename.

You are free to add other directories to your lesson. Images go in `images`, and
PDF files in `pdf`. For example, a lesson repository could look like:

~~~
01_management/
  index.md
  images/
    image1.png
    image3.jpg
  pdf/
    one-pager.pdf
~~~

## Markdown and github resources

**TODO** make a list with a few links

## Informations about the tools used

The markdown documents are rendered into a website using *Jekyll*. The slides
themselves are rendered using *remarkjs*. The rendering is done using github
pages, which builds the site from the `master` branch. You can build the site
locally with `jekyll serve -w`, and it will be available at
[http://localhost:4000] for you to review.

The stylesheets are defined in `resources/styles`, and rendered to
`resources/dataone.css` using `lessc` (just type `make` from the root).

## How to contribute

### Adding content

1. Create a fork of the repository into your github account
2. Modify the files that you want to change
3. Submit a pull-request against the `master` branch of this repository
4. Your changes will be reviewed

### Suggesting changes

1. Open an *Issue* **TODO ADD LINK** on this repository

## Documentation of specific functionalities

### Creating slides

### Adding notes

### Columns

### Full bleed pages

### Warning, information, and question boxes

### Code listings

### Video embedding
