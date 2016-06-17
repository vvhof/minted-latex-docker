# minted-latex-docker

A Docker Image to compile .tex including minted
## Usage

###Volumes 
/inputData

### command parameter
location of entrypoint .tex file that should be compiled

### example
```docker run -v <dir>:/inputData vvhof/mintedlatex <.tex inside <dir> location>```
