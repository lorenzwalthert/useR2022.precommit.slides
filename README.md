#  Creating xaringan slides using the useR! theme


Welcome to useR, in this repository you will find a template that shows the use of the "useR" xaringan theme. 

## Installation 

I you have not installed the xaringan package, run this command in your RStudio session:

```
if (!requireNamespace("remotes", quietly = TRUE))
    install.packages("remotes")

remotes::install_github("yihui/xaringan")
```

## Creating a presentation

Use the template.Rmd file with the 'useR' and 'useR-fonts' theme to start writing your conference presentation. 

Alternatively, use File > New file > Rmarkdown > From template > Ninja Presentation 
to start editing a new xaringan presentation. 


Add css: ["useR", "useR-fonts"] in the YAML header to specify that you want to use the useR and useR-fonts in your presentation.


## Rendering your presentation

To knit, click on the knit button or use rmarkdown::render(). Alternatively, you can knit and see a live preview using xaringan::inf_mr()


Here are some captions of how your presentation would looks like:

## Let's start with a title slide


<p align="center">
<img src="img/title.png"
     alt="An example of a title slide with the xaringan theme 'useR' including the conference logo in the top left corner and the presentation's title and presenter's name in the bottom left corner"
     width="500" 
     height="350" />
</p>


## We have provided font sizes that can be seen even from small screens.

<p align="center">
<img src="img/header.png"
     alt="An example slide showing the appropiate font size of the headers included in the xaringan theme configuration, as well as the font size of some R code"
     width="500" 
     height="350" />
</p>


## You can use the chapter slide to separate different sections in your presentation


<p align="center">
<img src="img/chapter.png"
     alt="A slide of class 'chapter' with blue background and the word 'Chapter' in light grey color at the left center of the slide"
     width="500" 
     height="350" />
</p>


## Also, you can include some code and results:

<p align="center">
<img src="img/plots.png"
     alt="In the left column: An example histogram created with the default ggplot2 color scale, showing three curves in pink, green and blue. In the right column: four panels showing how the histogram curves look with four different color-vision-deficiencies"
     width="500" 
     height="350" />
</p>


## If you are using ggplot2 to create plots, the [viridis](https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html) package is a good choice to set colorblind-friendly scales: 

<p align="center">
<img src="img/plots_viridis.png"
     alt="In the left column: The histogram created with ggplot2 now includes a colorblind-friendly scale, showing three curves in purple, green and yellow. In the right column: four panels showing how the histogram curves look with four different color-vision-deficiencies"
     width="500" 
     height="350" />
</p>


## Please, include Alternative text in your figures and make them screen-reader friendly.   


If this is your first time using alternative text, this [article](https://www.techsmith.com/blog/how-to-create-alternative-text-for-images-for-accessibility-and-seo/) could be helpful. Also, if you want to ensure that your alt-text is clear, you can activate a screen reader like [VoiceOver](https://webaim.org/articles/voiceover/), [NVDA](https://webaim.org/articles/nvda/) or [JAWS](https://webaim.org/articles/jaws/) and listen how your alternative text will sound. 


