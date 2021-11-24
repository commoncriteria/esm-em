Protection Profile Module for Enterprise Management (EM)
===============
[![Build](https://github.com/commoncriteria/esm-em/workflows/Build/badge.svg)](https://commoncriteria.github.io/pp/esm-em/esm-em-release.html)
[![Validate](https://github.com/commoncriteria/esm-em/workflows/Validate/badge.svg)](https://github.com/commoncriteria/esm-em/actions/workflows/validate.yml)
[![SanityChecks](https://raw.githubusercontent.com/commoncriteria/esm-em/badges/main/warnings-badge.svg)](https://github.com/commoncriteria/esm-em/blob/gh-pages/SanityChecksOutput.md)
[![SpellCheck](https://raw.githubusercontent.com/commoncriteria/esm-em/badges/main/spell-badge.svg)](https://github.com/commoncriteria/esm-em/blob/gh-pages/SpellCheckReport.txt)
[![QuickBuild](https://github.com/commoncriteria/esm-em/actions/workflows/quick_build.yml/badge.svg)](https://commoncriteria.github.io/esm-em/esm-em-release.html)
[![GitHub issues Open](https://img.shields.io/github/issues/commoncriteria/esm-em.svg?maxAge=2592000)](https://github.com/commoncriteria/esm-em/issues) 

This repository hosts the draft version of the Protection Profile Module for Enterprise Management based on the 
[Essential Security Requirements (ESR)](https://commoncriteria.github.io/pp/esm-em/esm-em-esr.html) for this technology class of 
products. This repository is used to facilitate collaboration and development on the draft document. 
See the [release](#Release-Version) section if you are looking for the officially released version for evaluations.
A list of products that have passed evaluation against this Protection Profile can be found [here](placeholder).

## Draft Version

* [Protection Profile Module for Enterprise Management](https://commoncriteria.github.io/pp/esm-em/esm-em-release.html) (html)
* [Supporting Document for Enterprise Management](https://commoncriteria.github.io/pp/esm-em/esm-em-sd.html) (html)
* [Protection Profile Module for Enterprise Management](https://commoncriteria.github.io/pp/esm-em/esm-em-release.pdf) (pdf)
* [Supporting Document for Enterprise Management](https://commoncriteria.github.io/pp/esm-em/esm-em-sd.pdf) (pdf)

## Release Version
* [Protection Profile Module for Enterprise Management]() (coming soon)

## Contributing

If you are interested in contributing directly to future versions the this Protection Profile, please consider joining the NIAP technical community.
* [How to join the NIAP Technical Community (Mailing list and updates)](https://www.niap-ccevs.org/NIAP_Evolution/tech_communities.cfm)

## Feedback

Questions, comments, and fixes can be submitted to the [repository issue tracker](https://github.com/commoncriteria/esm-em/issues)

## Quickstart
To clone this project along with its _transforms_ submodule run:

````
  git clone --recursive git@github.com:commoncriteria/qqqq.git
````
To pull updates from the upstream _transforms_ submodule and commit them run:
````
 git submodule update --remote transforms
 git add transforms
 git commit
````

### Development Info
[Help working with Transforms Submodule](https://github.com/commoncriteria/transforms/wiki/Working-with-Transforms-as-a-Submodule)

## Repository Content
* input - Contains the 'meat' of the project. It's the input content (in XML form) that gets transformed to readable html.
* output - The output directory where the html is placed after transformation.
* output/images - The directory where images are stored
* transforms - Points to the transform subproject which is really a repository for resources shared amongst many Common Criteria projects. You shouldn't need to modify it.

## Links 
* [National Information Assurance Partnership (NIAP)](https://www.niap-ccevs.org/)
* [Common Criteria Portal](https://www.commoncriteriaportal.org/)

## License
See [License](./LICENSE)
