# max-unmix
Max-UnMix code
The documents and data within this folder form the basis for the MAX UnMix application that can be accessed online at https://maxunmix.shinyapps.io/unmix_v8/. The code for the application can be found in the documents “server.R” and “ui.R”. 

Instructional videos are available online in the ‘Resources’ tab of the MAX UnMix webpage.

If you will be processing a large amount of data using MAX UnMix you may wish to run the program locally (offline). To run MAX UnMix locally on your own computer follow the steps below.

##########
1. Download BOTH R and R-studio to your computer. Instructions for downloads can be found at:
	R = https://www.r-project.org/
	R studio = https://www.rstudio.com/products/rstudio/download/

2. Save the MAX UnMix folder to your computer 

3. Open R-studio

4. In “Console” enter the following text and hit return: 
	
	install.packages("shiny") # load the shiny package into R
	setwd(“ENTER DIRECTORY YOU SAVE MAX UNMIX TO”) #tells R where to find app
	runApp(“MAX_UnMix”) #will launch app in browser or local R-studio window

############
If you encounter problems in operating MAX UnMix locally or online, please send all questions, comments, and concerns to Dan Maxbauer (maxba001@umn.edu).
