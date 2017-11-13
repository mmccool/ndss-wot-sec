# NDSS DISS 2018 Workshop Paper on WoT Security Model
Submission to the NDSS 2017 Workshop on Decentralized IoT Security and Standards (DISS):
[DISS](https://www.ndss-symposium.org/ndss2018/cfp-ndss2018-diss/).
Formatting follows the template and instructions 
[here](https://www.ndss-symposium.org/ndss2018/ndss-2018-templates/).

# Instructions
## Install TexLive
You need to install LaTeX.  On Ubuntu, you can use
```
    sudo apt-get install texlive-full
```
This installs a full version of TeXLive which is quite large;
you will need at least 3GB of free disk space.

## Compile Paper
After installation, you will be able to compile the paper with
```
    pdflatex ndss-wot-sec.tex
    bibtex ndss-wot-sec
    pdflatex ndss-wot-sec.tex
```
which will generate [ndss-wot-sec.pdf](ndss-wot-sec.pdf).
You generally only need to run the `bibtex` command and the second run
of latex if you updated a reference and the bibliography should be 
updated.
