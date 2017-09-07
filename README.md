# kit-jupyter-slides-theme

- (un)official css theme for KIT presentations with jupyter notebook slideshow

This repository contains some `css` and images to customize jupyter notebook presentation for KIT presentations. It is responsible and further customizable. 

# Try it

- Clone the repository
- execute `jupyter nbconvert slides.ipynb --to slides --post serve`

This should give you something like this: 

![screenshot](/screen1.png)

# How to use it (jupyter nbconvert)

- Clone this repository 
- Put the `custom.css` file and `ìmg` folder where your notebook (`.ipynb`) lives
- execute `jupyter nbconvert <yournotebook>.ipynb --to slides --post serve`

# How to use it (RISE)

For people using the RISE extension (https://github.com/damianavila/RISE/) 
- Clone this repository 
- Put the `custom.css` file and `ìmg` folder where your notebook (`.ipynb`) lives
- Add this to at the beginning of your notebook:

```python
%%HTML
<link rel="stylesheet" type="text/css" href="custom.css">
```

For example:

![screenshot](/screen2.png)

Then, it should work during live reveal. This is a bit hacky but ok. 

# Customize it

Modify whatever you want in the `css` file (this is pretty straightforward).

For example:
- Change the logos / logo paths
- The name in the footer
- The colors on the arrows and progress bar 

# Still to do

- better parametrization (using LESS or SAS for example)