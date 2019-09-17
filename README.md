# List of currently active shiny applications 
 * [Classifying Land Cover in the Elkhorn Slough](https://bnhm-shiny.berkeley.edu/ElkhornSloughPublic/) 2019 [[github repo](https://github.com/mvandop/ElkhornSloughPublic)]
 * [Hawaii Wildfire](https://bnhm-shiny.berkeley.edu/HWMO/) 2018 [[github repo](https://github.com/niklaslollo/HWMO_webapp)]
 * [California Plant Phylodiversity Atlas](https://bnhm-shiny.berkeley.edu/cappa/) 2018 [[github repo](https://github.com/matthewkling/cappa)]

# BNHM Shiny Server
A place to host Berkeley Natural History Museum [R Shiny](https://shiny.rstudio.com/) applications.  See the bottom of this page for links to applications which are hosted on the BNHM shiny server.  These are applications which have been submitted to the BNHM review team and have passed several checks.  

# Instructions for submitting shiny applications

Your application for running a shiny application on the bnhm-shiny server can be started by opening an issue in this repository using the onboarding template. Follow the instructions on the template to get started.  In general, we are looking for code that is maintained as a public repository in github, well written code, code documentation, a descriptive README.md file, and a list of dependencies. 
 
Please note that BNHM will host accepted applications from DS421 students and potentially other shiny applications of interest to BNHM for two years but does not guarrantee continued availability after that.  We will do our best to maintain code longer than 2 years as well as to give users a warning if the application needs to come down or if the server will not be available.
 
 # System Administration / Deployment Details
  * as user shiny, checkout code in /home/shiny/code on beagle
  * FIRST TIME ONLY: as root create a symbolic link to the applications app directory in /srv/shiny-server
  * test deployment and then add to the list of currently active shiny applications above



