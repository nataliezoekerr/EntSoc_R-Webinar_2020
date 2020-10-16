This "README.txt" file contains the same information as the markdown file in the master folder "README.md". 
You can open the "README" markdown file in R Studio. 


## FOR BOTH SESSIONS

Before reviewing the workshop content for both sessions. You will have to have both Program R (Version 3.2 or higher) and R Studio downloaded on your computer. 

   Program R - https://cloud.r-project.org/
   R Studio - https://rstudio.com/products/rstudio/


If you have both of these programs already downloaded, please check that you have R 3.2.0 or higher installed on your computer for both sessions. 
To check your R Version, you can run the following code in your R console: 

> R.Version()

Or navigate to "Tools -> Global Options -> General" and under "R Version", it will tell you the version that you currently have installed on your computer. 

If your R version is outdated for our sessions, you can follow the instructions here: 

     https://www.r-bloggers.com/2017/05/upgrade-r-without-losing-your-packages/

to avoid having to re-install all of your existing packages. You will only need to update program R, not R Studio. 

You can update R using the following "installr" package and code:
> install.packages("installr")
> require(installr)
> updateR()



## SESSION 2 ONLY 

Before continuing to session 2 on frequentist models. You will need the following packages installed. 
* here
* pscl
* glmmTMB
* lme4
* car
* lmtest
* bbmle

To install these packages, you can either navigate to the *"Files/Plots/Packages/Help/Viewer"* panel, click on "Packages" tab, then "Install" and type in each of the packages. Or you can use the following R code: 

> install.packages("here")

If you have some of these packages already installed, it might be good to also update these by going to the same panel and clicking "Packages" tab, then "Update" and 