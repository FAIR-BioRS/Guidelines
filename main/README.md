# FAIR Biomedical Research Software (FAIR-BioRS) guidelines draft v2.0.0

## 1. Prepare prior to the development of the software

1.1. Select a version control system platform to work from (e.g., [GitHub](https://github.com/), [Bitbucket](https://bitbucket.org/), [GitLab](https://gitlab.com/)) and create a repository there for your software.

1.2. Select a license and include the license terms in a LICENSE file located in the root directory of the software repository. While the FAIR4RS principles do not require research software to be open-source, it is highly recommended to use a license approved by the Open Source Initiative (OSI). Amongst those licenses, it is encouraged to use the permissive MIT or Apache 2.0 licenses. Use [choosealicense.com](https://choosealicense.com/) and/or the [SPDX License List](https://spdx.org/licenses/) for help. During development, ensure that the software’s license is compatible with the software’s dependencies.

## 2. Follow coding standards and best practices during development

2.1. Have code-level documentation (in code comments, description in the file headers).

2.2. Record dependencies as per standard practices for the coding language, e.g. in a requirements.txt file for Python code, in a package.json file for Node projects, or in a DESCRIPTION file for R packages.

2.3. Follow language-specific standards and best practices (e.g. [the PEP 8 Style Guide for Python Code](https://peps.python.org/pep-0008/), [Google’s R Style Guide](https://google.github.io/styleguide/Rguide.html) for R code, [Common Workflow Language (CWL)](https://www.commonwl.org/) for command line tools, etc.) and document them (c.f. 3.2).

2.4. Ensure that inputs/outputs of the software follow any applicable community standards (e.g., General Feature Format (GFF) for genomic annotations - c.f. [fairsharing.org](https://fairsharing.org/) for finding relevant standards). 

## 3. Document software 

3.1. Maintain the documentation in a README.md or README.txt file located in the root directory of the software. Mature/complex software may require additional, more sophisticated documentation that can be developed e.g. using tools such as [GitHub pages](https://pages.github.com/), [Read the Docs](https://readthedocs.org/), or [Docusaurus](docusaurus.io). The following aspects must be documented as applicable: 
- Overall description of the software (e.g., in an “About” section)
- High-level dependencies of the software (e.g., Node or Python version)
- Inputs and outputs of the software
- Parameters and data required to run the software
- The standards applied
- How to contribute to the software
- How to cite the software

3.2. Document changes between different versions of the software in a CHANGELOG.md or CHANGELOG.txt file. We suggest following the “[Keep a changelog](https://keepachangelog.com/)” conventions for the content of the CHANGELOG file and the [Semantic Versioning v2.0.0](https://semver.org/spec/v2.0.0.html) for version numbers.

## 4. Include metadata files

4.1. Include a codemeta.json metadata file in the root directory of the software. The [CodeMeta generator](https://codemeta.github.io/codemeta-generator/) can be used. Provide, at least, the following fields in the codemeta.json file: 
- Software name (“name”), Software description/abstract (“description”)
- Unique identifier ("identifier")
- Authors (“givenName”, “familyName”) with their Organization name (“affiliation”)
- Keywords (“keywords”)
- Programming Language (“programmingLanguage”)
- First and current release date (“dataPublished” and “dateModified”)
- License used (“license”).

When applicable, also provide the following fields: “isPartOf”, “hasPart”, and “relatedLink“.

4.2. Include a CITATION.cff metadata file in the root directory of the software. The [CFF file initializer](https://citation-file-format.github.io/cff-initializer-javascript/) can be used. Provide, at least, the following fields in the CITATION.cff file:
- Authors ("given-names", “family-names") with their Organization name (“affiliation”)
- Software description/abstract (“abstract”)
- Unique identifier ("identifiers")
- Keywords (“keywords”)
- License (“license”)
- Release date (“date-released”).


## 5. Share software on a repository

5.1. If applicable, share the software on a language-specific deployment repository e.g., [PyPI](https://pypi.org/) or [Conda](https://anaconda.org/anaconda/repo) for Python packages, [npm registry](https://www.npmjs.com/) for JavaScript packages, [CRAN](https://cran.r-project.org/) for R packages or [Bioconductors](https://www.bioconductor.org/) for R-packages aimed at the analysis of genomics data, [Dockstore](https://dockstore.org/) for Docker-based tools, etc. Do this for each version release of your software.

5.2. Share the software on the archival repository [Zenodo](https://zenodo.org/) (suggested) or [Figshare](https://figshare.com/). The source code of the software with all the above-mentioned metadata files must be shared. Executables must be shared as well if available. Do this for each version release of your software.

5.3. Archive the source code and all development history on [Software Heritage](https://www.softwareheritage.org/) directly from your version control system platform. You can use the [Software Heritage save code now page](https://archive.softwareheritage.org/save/). This is only required once as Software Heritage will then periodically archive your source code automatically. 

## 6. Register software on a registry
Optionally register the software on a registry such as [bio.tools](https://bio.tools/) or the [Research Resource Identifiers (RRID) Portal](https://scicrunch.org/resources/about/resource). This is only required once but should be updated if the registry-specific metadata needs to be updated.


