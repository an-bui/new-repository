
## General information

**Description**: This is an example repo for the Git/Github and README resources for ENVS 193DS, Spring 2024.  

**Collaborators**: An Bui, Caitlin Nordheim-Maestas  

**Research focus**: We visualized fiddler crab size as a function of latitude and site.

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

The rendered .html for this repo is [here](https://an-bui.github.io/new-repository/test-document.html).

**Note: you should have at least a "General information" section, a "Data and file overview" section, and a "Rendered output" section in your README for full credit.**

# Nice things to have

## Sharing and accessing information

This repository is under a Open Data Commons Public Domain Dedication and License (PDDL). Feel free to reuse and modify as you see fit!  

**Note:** you decide what license your work should be under. Licenses are community standards/norms, meaning that everyone respects them even though they do not have legal binding (yet). See this resource from Cornell Data Services about the [different types of licenses](https://data.research.cornell.edu/data-management/sharing/intellectual-property/#data-licensing).

## Methodological information

Data used in this repository come from the `lterdatasampler` package. Specifically, we use the `pie_crab` dataset of fiddler crab size from Plum Island Ecosystem LTER.   

Citation: Horst A, Brun J (2023). lterdatasampler: Educational Dataset Examples from the Long Term Ecological Research Program. R package version 0.1.1, https://github.com/lter/lterdatasampler.

## Data-specific information

| Columns         | Variable type | Content                              | Units       |
|:----------------|:--------------|:-------------------------------------|:------------|
| `date`          | Date          | date of collection                   | none        |
| `latitude`      | numeric       | collection site latitude             | degrees     |
| `site`          | character     | collection site code                 | none        |
| `size`          | numeric       | fiddler crab size                    | millimeters |
| `air_temp`      | numeric       | mean temperature                     | °C          |
| `air_temp_sd`   | numeric       | temperature standard deviation       | °C          |
| `water_temp`    | numeric       | mean water temperature               | °C          |
| `water_temp_sd` | numeric       | water temperature standard deviation | °C          |

**Note 1:** you can get the "variable type" information by running `str()` with your data frame in the console.  

**Note 2:** See [this guide](https://quarto.org/docs/authoring/tables.html) for how to make tables in markdown (i.e. outside of code).

# More information

For more information on how to write an informative README, see the UCSB Library Research Data Service's [guide](https://perma.cc/A5PN-YF7Z).
