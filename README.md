# ![Paper](docs/paper_github_banner.png)

LaTeX for the Thesis Paper following the provided template (document class _mscthesis.cls_) with small adoptions in the overall structure. The paper follows the provided guidelines for each section from the Master IS course. It is in ACM (double-column) format with a maximum length of 10 pages, references start from the second column of the tenth page excluding the appendix.

The cover photo of this paper is generated using [DALL·E 3](https://openai.com/index/dall-e-3/) using the prompt: _microcontroller chip front-facing the chip like a motherboard overgrown with moss and planters with on the bottom the GPIO pins hanging strings on a white background_.

## Tools and references
[Zotero](https://www.zotero.org/) was used as a citation management tool. Through the integration of the [Zotero connector plugin](https://www.zotero.org/download/connectors) into a web browser, relevant scholarly papers could be conveniently pinned to the appropriate folders for sorting and labeling to their respective topics. 

Furthermore, the integration of Zotero with the beta version of [Research Rabbit](https://www.researchrabbit.ai/), a tool designed to construct visual knowledge graphs of papers contained within [Zotero collections](https://www.researchrabbit.ai/tipsandtricks), was used. This integration facilitated the cross-referencing of papers and provided recommendations for related works based on similar works and references within the paper thereby enabling the exploration of subfields and author networks.

## Install

This paper was written in VSCode using the LaTeX Workshop Extension. The `.vscode` folder sets up the configuration environment for the correct building of the references using this structure.

1) Install a code editor such as [VSCode](https://vscode.dev/).
2) Install the [LaTeX Workshop extension](https://github.com/James-Yu/LaTeX-Workshop) for VSCode.
3) Clone this repository to your local machine.

```zsh
$ git clone git@github.com:viszlab/thesis-paper.git
```
4. Open the `setup.tex` file and [build the output .pdf](https://github.com/James-Yu/LaTeX-Workshop/wiki/Install#usage).


## Project structure

```
├── .vscode                 # LaTeX workshop configuration files
├── build                   # Output build files and build .pdf
├── docs                    # Documentation files and images
├── media                   # Images for figures and photographs
├── metadata                # .tex files for paper metadata 
├── sections                # .tex files for the main sections
├── mscthesis.cls           # Provided class template
├── references.bib          # References bib file
└── setup.text              # Includes packages and imports .tex
```

## Project
[**Viszlab**](https://wwww.viszlab.github.io) is a tangible physical data visualization for the [Lab42](https://lab42.uva.nl/) building. An interactive experience using environment sensor data to offer Human Building-Interaction. Viszlab is developed as a Thesis and Graduation project for the Master (MSc) Information Studies: [Information Systems](https://www.uva.nl/shared-content/programmas/en/masters/information-studies/information-studies.html) (track) at the [University of Amsterdam](https://www.uva.nl/en) by part-time student [Danny de Vries](https://www.dandevri.es/).

* **Master**: Master Information Studies: Information Systems (track)
* **University**: University of Amsterdam (UvA)
* **Institute**: Informatics Institute
* **Faculty**: Faculty of Science (FNWI)
* **Research Group**: Digital Interactions Lab (DIL)
* **Student**: BSc Danny de Vries (14495643)
* **Supervisor**: Dr. H. (Hamed) Seiied Alavi PhD

[Viszlab](https://www.viszlab.github.io) © 2024 by [Danny de Vries](https://wwww.github.com/dandevri) is licensed under [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1). 