# new-repository

# Essential components

## General information

This is where a general description of the repo would go. This could include (but is not limited to):  

- names of people working in the repo  
- where the data came from  
- broad research questions and analyses to address those questions  

## Data and file overview

- `test-document.qmd`: code to read in data and make plots  
- `test-document.html`: rendered version of `test-document.qmd`  
- `test-document_files`: accessory files for `test-document.html`  

Note that you can also get a tree diagram of all the files in the repo by running `tree` in the Terminal. You do have to install something new - see [directions here](https://superuser.com/questions/359723/mac-os-x-equivalent-of-the-ubuntu-tree-command).

```
.
├── README.md                   # broad overview
├── new-repository.Rproj        # project file
├── test-document.html          # rendered output
├── test-document.qmd           # raw code
└── test-document_files         # rendered files
    ├── figure-html             # figure output in .html file
    │   └── crab-plot-1.png     # stand alone .png file
    └── libs                    # accessory files to .html file
```

## Rendered output (specifically for this class)

For 193DS assignments, you should put a link to the rendered .html file here so that it is easy to access. For example, the rendered .html for this repo is [here](https://an-bui.github.io/new-repository/test-document.html).

**Note: you should have at least a "General information" section, a "Data and file overview" section, and a "Rendered output" section in your README for full credit.**

# Nice things to have

## Sharing and accessing information

This is where any information regarding data/code reuse and access would go. This is mostly relevant if you're working with your own data or data that your collaborators have collected.

## Methodological information

This is where any information about the methods used to collect, clean, or wrangle the data could go. If you do any cleaning/wrangling outside of the code (for example, directly in the .csv file), then you should describe what you did in this section.

## Data-specific information

This is where the metadata would go if you don't have a metadata file or sheet in your repository.

# More information

For more information on how to write an informative README, see the UCSB Library Research Data Service's [guide](https://perma.cc/A5PN-YF7Z).
