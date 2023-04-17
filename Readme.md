# ESG Reporting Platform
## Objective
The World Economic Forum (WEF), alongside related international development
organisations, is seeking to improve the ways that companies measure and
demonstrate their contribution to a more prosperous and fulfilled society and a more
sustainable relationship with our planet. In light of this, the objective of this project is to design and build a blockchain-enabled ESG compliance tracker which will function as a global solution for non-financial ESG reporting. The tracker will enable investors to make informed decisions based on a firm’s sustainability performance, and regulators to view voluntary disclosures by firms.

The ESG compliance tracker should be based on the WEF’s 21 core stakeholder
capitalism metrics (https://www.weforum.org/stakeholdercapitalism/our-metrics). These
metrics are primarily quantitative in nature, and widely considered to be a good entry
point and baselining mechanism for companies embarking on their ESG reporting
journeys.

The platform should:
- Allow a firm to initiate an annual ESG reporting exercise for a given reporting
period/year. A firm may select and report on the metrics that are applicable to
their line of business.
- Allow a firm to submit a completed annual ESG compliance form to the
blockchain (at which point the firm can no longer edit the submission). NB -
assume that the data submitted to the blockchain is valid although in practice, a
trusted third party will validate this data before it is committed to the blockchain.
- On submission of an ESG report, an NFT should be minted and transferred to
the firm responsible for the submission. The metadata of the NFT should include
the ESG reporting period, and links to the blockchain transaction explorer
entry(s) for the ESG submission.
- On submission of an ESG report, a standardised ESG report (PDF format) for the
firm and reporting period in question should be generated. The report should also
include links to the relevant blockchain entries.
- Allow regulators/supervisors and investors to view generated ESG reports (for
firms that have carried out reporting in the period).
- Provide investors with visual representations of the ESG data, including graphs
and charts, to make it easier to understand the data.
- Allow investors to compare ESG reports for multiple firms for a given period
(optional).

## Development Team

__Development Team 1__
| Name | Role |
| --- | --- | 
| Your Name Here | Developer |
| Your Name Here | Developer |
| Your Name Here | Developer |

__Development Team 2__
| Name | Role |
| --- | --- |
| Yashkir Ramsamy | CTO, Developer |
| Your Name Here | Developer |
| Your Name Here | Developer |


# How to Contribute to this Project (Tutorial)
This is a beginner-friendly guide on how to create a pull request and add your name to the README file. We will be using pull requests to keep track of the contributors to this project, as well as to merge the changes you make to the codebase.

## Pre-requisites
Before you can contribute to this project, you need to have a basic understanding of the following:

 - Git and GitHub
    - You need to setup [Git](https://git-scm.com/downloads) on your computer and have a GitHub account. 
- SSH Access to GitHub
    - You need to setup ssh-access to your GitHub account. You can follow this [guide](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh) to setup ssh-access to your GitHub account. Another alternative is to Search "Add SSH Key to GitHub" on YouTube for a video tutorial.

## What is a pull request?

A pull request is a way to suggest changes to a project on GitHub. When you create a pull request, you are proposing changes to the original codebase. The project maintainers can review your changes and decide whether or not to merge them into the main codebase.

## How to create a pull request

1. Fork the repository - To create a pull request, you first need to fork the repository. This will create a copy of the project in your GitHub account that you can modify.

2. Clone the forked repository - After forking, clone the forked repository to your local machine. You can do this by running the following command in your terminal:

```git clone https://github.com/<your-username>/<repository-name>.git```

3. Create a new branch - Before making any changes, create a new branch. This will help you keep your changes separate from the main branch. You can create a new branch by running the following command:

```git checkout -b <yourName-feature-change>```

`<yourName-feature-change>` is the name of the branch you want to create. You can name the branch anything you want, but it's a good idea to name it something that describes the changes you are making. For example, if you are adding your name to the README file, you can name the branch `yashkir-readMe-updateTeamMember`.

4. Make changes - Now you can make changes to the code. In this case, you want to add your name to the README file. Open the README file in a text editor and add your name to the list.

6. Push changes to GitHub - After committing your changes, you need to push them to your forked repository. You can do this by running the following command:

```git push origin <branch-name>```

7. Create a pull request - Finally, you can create a pull request by navigating to your forked repository on GitHub and clicking the "New pull request" button. Select the branch you just created and click "Create pull request". Add a title and description for your pull request, and then click "Create pull request" again.

