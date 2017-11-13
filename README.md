# NDSS DISS 2018 Workshop Paper on WoT Security Model
Submission to the 
[NDSS 2018 Workshop on Decentralized IoT Security and Standards (DISS)](https://www.ndss-symposium.org/ndss2018/cfp-ndss2018-diss/).
Formatting follows the template and instructions 
[here](https://www.ndss-symposium.org/ndss2018/ndss-2018-templates/).

## Instructions
### Install TexLive
You need to install LaTeX.  On Ubuntu, you can use
```
    sudo apt-get install texlive-full
```
This installs a full version of TeXLive which is quite large;
you will need at least 3GB of free disk space.

### Compile Paper
After installation, you will be able to compile the paper with
```
    pdflatex ndss-wot-sec.tex
    bibtex ndss-wot-sec
    pdflatex ndss-wot-sec.tex
```
which will generate [ndss-wot-sec.pdf](ndss-wot-sec.pdf).
You generally only need to run the `bibtex` command and the second run
of `pdflatex` if you updated a reference and the bibliography should be 
updated.  Note also the use of `pdflatex` to generate a PDF file
directly.

## Themes
Here are some possible topics to discuss in the paper, targetting
the "decentralized security" focus of the workshop:
* Vulnerability scanning using metadata. There is both risk and opportunity.
* End-to-end secure adaptation: translate payloads in secure endpoints, not at bridges.
* Secure semantic searches.  How to ensure only authorized things are searched when using federated semantic searches?
* Metadata for distributed security and payment mechanisms, eg. Interledger.
