# overleaf_assignment

## LATEX can be compiled through Terminal with "texlive" as below:
For MacOS:
<ol>
<li> Install TexLive: </li>

  ```
  brew install texlive
  ```

Make sure *pdflatex* is ready to work: 
  ``` 
  pdflatex --version 
  ```

<li> Compile option: </li>
<ul>
<li> Compile to *pdf* file with *pdflatex*</li>

  ```
  pdflatex [tex_file].tex
  ```
  For example: ```pdflatex main.tex```
<li> Compile to *.dvi* file with *latex*:</li>

  ```
  latex [tex_file].tex
  ```
  For example: ```latex main.tex```
<li> Convert *.dvi* file to PostScript file:</li>

  ```
  dvips -o [output].ps [input].dvi
  ```
  For example: ```dvips -o main.ps main.dvi```
<li> Convert *.dvi* file to PDF file:</li>

  ```
  dvipdfm [filename].dvi
  ```
  For example: ```dvipdfm main.dvi```
</ul>


<li> Packages can be installed by TexLive Manager:</li>

```
tlmgr install [package_name]
```
For example: ```tlmgr install multirow```
</ol>
