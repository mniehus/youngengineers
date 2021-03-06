# Young Engineers Club Curriculum

This is a curriculum for a teacher/facilitator to use in a secondary school
weekly young engineers educational program.

For a formatted compilation of all the information here, check out
[Young_Engineers_Club_Curriculum.pdf](https://github.com/artdavis/youngengineers/blob/master/Young_Engineers_Club_Curriculum.pdf).
The rendered html document is available in [Young_Engineers_Club_curriculum.html](http://htmlpreview.github.io/?https://github.com/artdavis/youngengineers/blob/master/Young_Engineers_Club_Curriculum.html).

The documentation here is written in [asciidoc](http://asciidoc.org/) format.
You can build the pdf document via docbook:
```bash
a2x Young_Engineers_Club_Curriculum.asciidoc
```

If you're not getting the admonition icons in the document on Linux this
may do the trick:
```bash
a2x -f pdf --icons --dblatex-opts='-I /etc/asciidoc/images/icons' Young_Engineers_Club_Curriculum.asciidoc
```

Also handy to build as an html document:
```bash
a2x -f xhtml --icons Young_Engineers_Club_Curriculum.asciidoc
```

The `demos/` directory present non-interactive lessons that may be
useful to run before launching into a challenge.

The `workshops/` directory contain the challenges that may be used to
fill an academic year for a club that meets weekly.

The `supplemental/` directory contains additional challenges that you may
want to use to fill time or plug in outside of the regular workshop
curriculum.


# License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
<img alt="Creative Commons License"
     style="border-width:0"
     src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />
<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">
Young Engineers Club Curriculum</span> by
<a xmlns:cc="http://creativecommons.org/ns#"
   href="mailto:art.davis@gmail.com"
   property="cc:attributionName"
   rel="cc:attributionURL">Arthur Davis</a> is licensed under a
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />
Original work is available at
<a xmlns:dct="http://purl.org/dc/terms/"
   href="https://github.com/artdavis/youngengineers"
   rel="dct:source">https://github.com/artdavis/youngengineers</a>.
