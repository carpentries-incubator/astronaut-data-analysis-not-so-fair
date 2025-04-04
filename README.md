[![DOI](https://zenodo.org/badge/776011771.svg)](https://zenodo.org/doi/10.5281/zenodo.12699084)

## Not so good astronaut data analysis code

This repository contains a helper software project with some code to be used 
for the ["Software tools and practices for open and reproducible research" course](https://github.com/carpentries-incubator/fair-research-software). 

This repository is an example of "not so good" software that is meant to be improved over the course to show examples of better research software practices (including some aspects of FAIR). 

Various branches of this repository represent the state of the code as it should be at the start of each of the course episodes:

- Episodes ["1. Course introduction"](https://carpentries-incubator.github.io/fair-research-software/01-introduction.html), ["2. FAIR research software"](https://carpentries-incubator.github.io/fair-research-software/02-fair-research-software.html) and ["3. Tools and practices for FAIR RS development"](https://carpentries-incubator.github.io/fair-research-software/03-tools.html) are not making changes to the software
- [branch 04-version-control](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/04-version-control) matches the code at the start of episode ["4. Version control"](https://carpentries-incubator.github.io/fair-research-software/04-version-control.html)
- [branch 05-code-environment](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/05-code-environment) matches the code at the start of episode ["5. Reproducible development environment"](https://carpentries-incubator.github.io/fair-research-software/05-code-environment.html)
- [branch 06-code-readability](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/06-code-readability) matches the code at the start of episode ["6. Code readability"](https://carpentries-incubator.github.io/fair-research-software/06-code-readability.html)
- [branch 07-code-structure](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/07-code-structure) matches the code at the start of episode ["7. Code structure"](https://carpentries-incubator.github.io/fair-research-software/07-code-structure.html)
- [branch 08-code-correctness](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/08-code-correctness) matches the code at the start of episode ["8. Code correctness"](https://carpentries-incubator.github.io/fair-research-software/08-code-correctness.html)
- [branch 09-code-documentation](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/09-code-documentation) matches the code at the start of episode ["9. Code documentation"](https://carpentries-incubator.github.io/fair-research-software/09-code-documentation.html)
- [branch 10-open-collaboration](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/10-open-collaboration) matches the code at the start of episode ["10. Open code & collaboration"](https://carpentries-incubator.github.io/fair-research-software/instructor/10-open-collaboration.html)
- Finally, repository [astronaut-data-analysis-fair repository](https://github.com/carpentries-incubator/astronaut-data-analysis-fair) contains the code that participants should have at the end of the course (an example of a good software project structure and code)


### What the code does
The code uses the [NASA data on human space walks (Extravehicular activities - EVAs)](https://data.nasa.gov/Raw-Data/Extra-vehicular-Activity-EVA-US-and-Russia/9kcy-zwvn/data_preview), 
exported/downloaded in JSON format, does some analysis over this data, plots a few graphs and saves the data in CSV format. 

### Things to improve
There is a number of things that are wrong or not so FAIR with this code and that can be improved. We maintain that list at issue
https://github.com/carpentries-incubator/astronout-data-analyses-bad/issues/2.

### Better code
An example of better and more FAIR code that participants should strive to achieve when writing their reseach software 
can be found at the [astronaut-data-analysis-fair repository](https://github.com/carpentries-incubator/astronaut-data-analysis-fair), 
to be used in conjuction with this repository during the course - this is the code that participants should have at the end of the course.

### License

Copyright of code in this project remains with [authors](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/graphs/contributors) or their organisations and is licensed under [MIT licence](LICENSE). For data used - see [data section](#data).

### Acknowledgements

#### Data

The data used on in this project is open data provided by NASA and obtained as follows.

Data source: https://data.nasa.gov/Raw-Data/Extra-vehicular-Activity-EVA-US-and-Russia/9kcy-zwvn/about_data.

Either export data from the above page using the `Export` button or download in JSON format from command line as: 

`curl https://data.nasa.gov/resource/eva.json --output eva-data.json`

**Note: the original data has been modified for the purposes of this tutorial by inserting a semicolon separator after each name in the `crew` field.**

#### HIFIS 
The idea for this software has been borrowed from the ["Astronaut analysis" workshop material](https://gitlab.com/hifis/hifis-workshops/make-your-code-ready-for-publication/astronaut-analysis) 
by [Helmholtz Federated IT Services (HIFIS)](https://gitlab.com/hifis).

#### Software Sustainability Institute and UKRN

This work has been supported by the [UK's Software Sustainability Institute](https://software.ac.uk) via the [EPSRC, BBSRC, ESRC, NERC, AHRC, STFC and MRC grant EP/S021779/1](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/S021779/1)
and [UK Reproducibility Network (UKRN)](https://www.ukrn.org/).


#### Software Sustainability Institute and UKRN

This work has been supported by the [UK's Software Sustainability Institute](https://software.ac.uk) via the [EPSRC, BBSRC, ESRC, NERC, AHRC, STFC and MRC grant EP/S021779/1](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/S021779/1)
and [UK Reproducibility Network (UKRN)](https://www.ukrn.org/).
