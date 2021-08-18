# LaTeX snippets

This repository contains LaTeX snippets and templates. 

In order to use the *.sty files, copy the appropriate subdirectory of

```
    kpsewhich -var-value=TEXMFHOME
```

For example, if the name of the *.sty file is `foo.sty,` then copy the file to 
```
    $(kpsewhich -var-value=TEXMFHOME)/tex/latex/foo/foo.sty
```
