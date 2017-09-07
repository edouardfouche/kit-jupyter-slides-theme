# kit-jupyter-slides-theme

(in)official css theme for KIT presentations with jupyter notebook slideshow

This folder contains some `css` and images to customize jupyter notebook presentation to for KIT presentations. It is reponsible and further customizable. 

# Try it

- Clone the repository
- execute `jupyter nbconvert slides.ipynb --to slides --post serve`

This should give you something like this: 

![screenshot](/img/screen1.png)

# How to use it

- Clone the repository 
- Put the `custom.css` file and `ìmg` folder where your slides (`.ipynb`) lives
- execute `jupyter nbconvert <yourslides>.ipynb --to slides --post serve`

# Customize it

Modify whatever you want in the `css` file (this is pretty straightforward)

For example:
- The two logo
- The name of the slide in the footer
- The colors on the arrow and progress bar 

# Still to do

- better parametrization (using LESS or SAS for example)