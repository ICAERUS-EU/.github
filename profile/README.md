<div align="center">
  <p>
    <a href="https://icaerus.eu" target="_blank">
      <img width="50%" src="https://icaerus.eu/wp-content/uploads/2022/09/ICAERUS-logo-white.svg"></a>
    <h3 align="center">ICAERUS GitHub Tutorial🦚</h3>
    
   <p align="center">
    Tutorial to use the ICAERUS github.
    <br/>
    <br/>
    <br/>
    <br/>
    <a href="https://github.com/icaerus-eu/icaerus-repo-template/issues">Report Bug</a>
    -
    <a href="https://github.com/icaerus-eu/icaerus-repo-template/issues">Request Feature</a>
  </p>
</p>
</div>

![Downloads](https://img.shields.io/github/downloads/icaerus-eu/icaerus-repo-template/total) ![Contributors](https://img.shields.io/github/contributors/icaerus-eu/icaerus-repo-template?color=dark-green) ![Forks](https://img.shields.io/github/forks/icaerus-eu/icaerus-repo-template?style=social) ![Stargazers](https://img.shields.io/github/stars/icaerus-eu/icaerus-repo-template?style=social) ![Issues](https://img.shields.io/github/issues/icaerus-eu/icaerus-repo-template) ![License](https://img.shields.io/github/license/icaerus-eu/icaerus-repo-template) 

## Table Of Contents

* [Summary](#summary)
* [Join ICAERUS-EU GitHub](#join-icaerus-eu-github)
* [Add your Use Case repository to ICAERUS-EU GitHub](#add-your-use-case-repository-to-icaerus-eu-github)
* [Add-the-README-template](#add-the-readme-template)
* [Repository requirements](#repository-requirements)
* [Managing your repository](#managing-your-repository)
* [Adding new models](#adding-new-models)
* [Authors](#authors)
* [Acknowledgements](#acknowledgements)
  
## Summary
This GitHub README is designed as a tutorial and template for the ICAERUS-EU project.  


## Join ICAERUS-EU GitHub
First of all, **it is necessary that you join ICAERUS-EU GitHub**. If you are not a member yet, please send an email to [jurrian.doornbos@wur.nl](mailto:jurrian.doornbos@wur.nl?subject=ICAERUS-Github-access) with your GitHub account information: email/username.


## Add your Use Case repository to ICAERUS-EU GitHub

### If you already have a UC Github repository
If you already have your own UC github repository, you would need to transfer it to the ICAERUS-EU GitHub ([tutorial](https://docs.github.com/en/repositories/creating-and-managing-repositories/transferring-a-repository)). 

1. Go to your repository and click on `Settings`
2. Scroll down to `Danger Zone`
3. Click on transfer to `ICAERUS-EU`
4. Update your local repository clones (download the transferred repository from ICAERUS-EU GitHub and make sure that all the URLs in the headers, image, etc. reflect this transfer: `https://github.com/jurriandoornbos/uavgeo` -> **`https://github.com/icaerus-eu/uavgeo`**).
   

### If you do not have a UC Github repository 
If you haven't created your UC Github repository yet, you can create one directly in the ICAERUS GitHub:

1. Go to `ICAERUS-EU GitHub`
2. Click on `repositories -> New`
3. Add your repository name, e.g. `UC1_Crop_Monitoring`
4. Click on `Public` and `Add a README file`


Useful links:
- [Creating a repo on GitHub](https://docs.github.com/en/get-started/quickstart/create-a-repo)
- [Youtube GitHub tutorial](https://www.youtube.com/watch?v=HkdAHXoRtos) 



## Add the README template
Update your readme with this template and fill it with your UC information.

### Header
You can copy-and-paste the header and shields directly into your own readme file (please change the `repo-title` in the urls to the correct ones).
```markdown
<div align="center">
  <p>
    <a href="https://icaerus.eu" target="_blank">
      <img width="50%" src="https://icaerus.eu/wp-content/uploads/2022/09/ICAERUS-logo-white.svg"></a>
    <h3 align="center">TITLE OF YOUR REPO/PROJECT🦚</h3>
    
   <p align="center">
    Short description of the content/subject matter in the repository
    <br/>
    <br/>
    <a href="https://github.com/icaerus-eu/repo-title/wiki"><strong>Explore the wiki »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/icaerus-eu/repo-title/issues">Report Bug</a>
    -
    <a href="https://github.com/icaerus-eu/repo-title/issues">Request Feature</a>
  </p>
</p>
</div>

![Downloads](https://img.shields.io/github/downloads/icaerus-eu/repo-title/total) ![Contributors](https://img.shields.io/github/contributors/icaerus-eu/repo-title?color=dark-green) ![Forks](https://img.shields.io/github/forks/icaerus-eu/repo-titlee?style=social) ![Stargazers](https://img.shields.io/github/stars/icaerus-eu/repo-title?style=social) ![Issues](https://img.shields.io/github/issues/icaerus-eu/repo-title) ![License](https://img.shields.io/github/license/icaerus-eu/repo-title) 
```
### Table of contents
We also expect a Table of Contents directly after the header, with linked section like the one in this repo, some ideas for sections are given below. 
```markdown
## Table Of Contents
- [Summary](#summary)
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [Development](#development)
- [Testing](#testing)
- [Documentation](#documentation)
- [License](#license)
- [Support](#support)
- [Security](#security)
- [Acknowledgments](#acknowledgments)
- [Resources](#resources)
- [FAQ](#faq)
- [Gallery](#gallery)
- [Deployment](#deployment)
- [Demo](#demo)
- [Dependencies](#dependencies)
- [Known Issues](#known-issues)
- [Roadmap](#roadmap)
```

Please include the `Acknowledgments` section  with EU-funding acknowledments.

```markdown
## Acknowledgements
This project is funded by the European Union, grant ID 101060643.

<img src="https://rea.ec.europa.eu/sites/default/files/styles/oe_theme_medium_no_crop/public/2021-04/EN-Funded%20by%20the%20EU-POS.jpg" alt="https://cordis.europa.eu/project/id/101060643" width="200"/>

```

## Adding new models 
To add new models to your repository you must follow the next structure: 

- models/XX_<model_name>/
  - README.md
  - best.pt

where `XX` is the actual number of the model (01,02,...). Then inside de models folder you will have one folder per model with its own documentation and weights or code. The `README.md` file should be structure as the example in [UC1 model](https://github.com/ICAERUS-EU/UC1_Crop_Monitoring/tree/main/models/01_plant_disease_detection_yolov8). Having the following information: 

**Model name** 
- Description, here it can be included a link to the code used for the development or training of the model.
- Dataset
- Input
- Output
- Type
- Date
- An image of the performance expected 

The end of the document will show the `Authors` and the `Acknowledgements` as in this template. The content on every folder can be adjusted for every model depending on its necessities but the main idea is that here we find the model to execute over the code.

In the main `README.md` of your repository you will have to include the references to each model folder. You can follow the structure of [UC1 MAIN README](https://github.com/ICAERUS-EU/UC1_Crop_Monitoring/tree/main). There is a reference for the models folder and a reference per model with a brief description.



### Update the *platform.json* template for WP6 Platform integration
To help out findability, and usability in the ICAERUS platform (WP6), the repo's should include a `platform.json`, following the template included in [Icaerus_Template](https://github.com/ICAERUS-EU/icaerus-repo-template/blob/main/platform.json). Then fill in the required information of your model to the file in your repo. In this template, you should also add the url for the specific model folder and the image reference of the performance expected. You can look at the example [UC1 PLATFORM JSON](https://github.com/ICAERUS-EU/UC1_Crop_Monitoring/blob/main/platform.json). 

This information will be used to upload the [ICAERUS PLATFORM](https://www.platform.icaerus.eu/) so its implementation it's extremely important. As every UC uploads their models and updates the `platform.json`, we will monthly translate this information to the main `platform.json` located in the [ICAERUS_DDAL](https://github.com/ICAERUS-EU/ICAERUS_DDAL/tree/main) that is the one used for the integration with the platform. 



## Repository requirements
### License
The Drone Data Analytics Library is open source, allowing anyone to view, modify, and contribute to its development. Contributors have the flexibility to choose from several open-source licenses as defined by the Open Source Initiative (OSI). You can explore these options at [OSI's official site](https://opensource.org/licenses).

Some popular open-source licenses allowed in the DDAL:
 - CC-BY: Creative Commons Attribution license, allowing use and modification as long as proper credit is given.
 - Apache 2.0: A permissive license that provides an express grant of patent rights to users and requires attribution.
 - MIT: A simple and permissive license, allowing reuse with minimal restrictions, only requiring attribution.
 - GPLv3: A copyleft license that ensures any derivative work must also be open source under the same license.
   
### Folder structure
From there on in, you can decide on folder structure which makes the most sense for the project. For some ideas of folder structures you can do [some research](https://mitcommlab.mit.edu/broad/commkit/file-structure/), or use what is already logical to you/your organization.
```
Ideas:
- .github/                   # GitHub-specific files and templates
  - workflows/               # Workflow configuration files (e.g., CI/CD)
- docs/                      # Documentation files (e.g., user guides)
- src/                       # Source code for your project
- tests/                     # Test files
- data/                      # Data files (if applicable)
- config/                    # Configuration files
- scripts/                   # Utility scripts
- public/                    # Publicly accessible assets (e.g., web assets)
- dist/                      # Compiled or distribution files
- examples/                  # Example code or usage examples
- LICENSE                    # Your project's license file
- README.md                  # Repository README
```

You can also check out [`uavgeo`](https://github.com/icaerus-eu/uavgeo) for an example `python` project folder/file structure that is published and available through `pip`. Or [`p2p-ros`](https://github.com/jurriandoornbos/p2p_ros) for a ROS related project.

## Managing your repository 

Some useful steps to manage your repository: 
- Create issues
  - In your repository, go to `Issues` and create a new issue, e.g. *Get train images for model detection algorithm*
  - This issue will be referred as a number in order of creation, e.g. *#1*
  - Use this reference in your commits
- To manage your repository from your local machine, go to the directory where you want to save your repo using the *cmd* and execute: 
  - `git clone <repository url>` 
- To update new files, using your cmd, go to the repo directory and execute: 
  - `git add .`
  - `git commit -m "Extracting plant images for model #1"`
  - `git push`
- Create a `.gitignore` to avoid uploading images or other data


## Authors

* **Jurrian Doornbos** - *Wageningen University* - [Jurrian Doornbos](https://github.com/jurriandoornbos)
* **Esther Vera** - *Noumena* - [Esther Vera](https://github.com/EstherNoumena)

## Acknowledgements
This project is funded by the European Union, grant ID 101060643.

<img src="https://rea.ec.europa.eu/sites/default/files/styles/oe_theme_medium_no_crop/public/2021-04/EN-Funded%20by%20the%20EU-POS.jpg" alt="https://cordis.europa.eu/project/id/101060643" width="200"/>
