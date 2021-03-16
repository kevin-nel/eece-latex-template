# eece-latex-template-2019

A latex template for electronic engineering reports at the University of Pretoria.
Slightly modified from the one provided by the module EM310 

## using the macros

### images next to each other

```tex
\vspace{2.5mm}
\begin{figure}
    \subpic{path/to/image.png}{some nice caption text}{fig:image_example}
    \subpic{path/to/image2.png}{some nice caption text}{fig:image2_example}
\end{figure}
\vspace{2.5mm}
```

### smaller oscilloscope images

```tex
\oscpic{path/to/image.png}{some nice caption text}{fig:image_example}
```

### inserting python

```tex
\inputpython{path/to/code.py}{caption about the script}{code:label}
```