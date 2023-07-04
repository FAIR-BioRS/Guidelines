[![Contributors][contributors-shield]][contributors-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![CC BY 4.0][cc-by-shield]][cc-by]
[![Curated with FAIRshare][fairshare-shield]][fairshare-url]
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6604538.svg)](https://doi.org/10.5281/zenodo.6604538)

[contributors-shield]: https://img.shields.io/github/contributors/FAIR-BioRS/Guidelines.svg?style=flat-square
[contributors-url]: https://github.com/FAIR-BioRS/Guidelines/graphs/contributors
[stars-shield]: https://img.shields.io/github/stars/FAIR-BioRS/Guidelines.svg?style=flat-square
[stars-url]: https://github.com/FAIR-BioRS/Guidelines/stargazers
[issues-shield]: https://img.shields.io/github/issues/FAIR-BioRS/Guidelines.svg?style=flat-square
[issues-url]: https://github.com/FAIR-BioRS/Guidelines/issues
[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
[fairshare-shield]: https://raw.githubusercontent.com/fairdataihub/FAIRshare/main/badge.svg
[fairshare-url]: https://fairdataihub.org/fairshare

# FAIR Biomedical Research Software (FAIR-BioRS) guidelines

## About
This repository is meant to maintain the FAIR Biomedical Research Software (FAIR-BioRS) guidelines and its different versions as well as collect community feedback. The [Findable, Accessible, Interoperable, and Reusable (FAIR) guiding principles](https://doi.org/10.1038/sdata.2016.18) published in 2016 constitute the foundation for data management practices adopted by researchers, government agencies, private funders, and scholarly publishers to ensure optimal reusability of data by humans and machines. While postulated for all digital research objects, they fail to capture the specific traits of software such as dependencies and versioning. Consequently, reformulated FAIR guiding principles tailored for software have been proposed. Work from the [Research Data Alliance (RDA) FAIR for Research Software (FAIR4RS) Working Group](https://doi.org/10.15497/RDA00065) is the most extensive on the topic. Just like the original FAIR guiding principles, the FAIR4RS guiding principles are aspirational and do not provide practical instructions and actionable items to the researchers. To fill this gap, we derived the first minimal and actionable step-by-step guidelines for biomedical researchers to make their research software compliant with the FAIR4RS principles. We designate these guidelines as the **FAIR Biomedical Research Software (FAIR-BioRS) guidelines**. Our process for developing these guidelines, based on a thorough review of current practices in the field, is available in our associated manuscript. We refer to the [FAIR-BioRS Hub repository](https://github.com/FAIR-BioRS/Hub) for a link to the manuscript and other related resources.

## Guidelines
The latest version of the guidelines is available in the [main folder](main).

## Structure of the repository
Each version of the guidelines are stored in a dedicated folder under the `versions` folder. An assessment of the compliance of the FAIR-BioRS guidelines with the FAIR4RS principles is also included with each version. The `main` folder contain a copy of the latest release folder where edits/suggestions can be made via pull request. At the time of the release of a new version of the guidelines, the `main` folder will be copied in the `versions` folder and renamed after the new version number. Changes between the different versions are tracked in the [CHANGELOG](https://github.com/FAIR-BioRS/Guidelines/blob/main/CHANGELOG.md) file. 

## Feedback and contribution
Use the [GitHub issues](https://github.com/FAIR-BioRS/Guidelines/issues) for submitting feedback or making suggestions. You can also fork the repository and submit a pull request with suggestions. Make your suggestions on the `main` folder of the main branch if making suggestions on the last released version or on the `main` folder of the staging branch if making suggestions on the lastest draft version (suggested).

## License
This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

## How to cite

If you are using or mentioning these guidelines, please cite the following:

- The associated manuscript:

```bash
    Patel, B., Soundarajan, S., Ménager, H. & Hu, Z. (2023). Making Biomedical Research Software FAIR: Actionable Step-by-step Guidelines with a User-support Tool. bioRxiv, https://doi.org/10.1101/2022.04.18.488694.
```

- The Zenodo archive of this repository:

```bash
    Patel, B., Soundarajan, S., Ménager, H. & Hu, Z. (2023). FAIR Biomedical Research Software (FAIR-BioRS) guidelines (v2.0.0). Zenodo. https://doi.org/10.5281/zenodo.6609011
```


## Acknowledgements

- [NIAID](https://www.niaid.nih.gov/) (Funding source up to July 2022)
- [The Butte Lab](https://buttelab.ucsf.edu/) (Collaborators)


