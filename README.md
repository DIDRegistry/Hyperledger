# Hyperledger Registry

This repository contains the source for the **did:git:github:Hyperledger** DID Method specification. The initital content was transferred from a collaborative HackMD document.

The current version of the spec is rendered here: 

To contribute to the specification, please submit a pull request by:

Forking the repo
editing the appropriate markdown files in the /spec folder
The specification is rendered from the markdown files to the index.html specification file in the /docs folder using Spec-Up. The full guidance for using SpecUp is in that documentation. The short version of the instructions for this repository is:

Install prerequisites: 
Install DRman: https://github.com/DIDMan/Drman
When you create a PR to update the specification, please DO NOT include docs/index.html. A GitHub Action on merge of PRs automagically renders for the full specification (docs/index.html) to the gh-pages branch in the repo and the specification is published from there. If there is a way to .gitignore the index.html in the main branch but not in the gh-pages branch, please let us know.

