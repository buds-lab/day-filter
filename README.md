#DayFilter Process

###created by [Clayton Miller](https://www.researchgate.net/profile/Clayton_Miller2)
Builds upon a series of Commercial Open Building Datasets on [datadrivenbuilding.org](http://datadrivenbuilding.org/)

This notebook will implement the first part of the DayFilter Process on data from the [United World College of South East Asia Tampines Campus in Singapore](https://www.uwcsea.edu.sg/east-campus). 

###The DayFilter Process is outlined an [Automation in Construction publication](https://www.researchgate.net/publication/266616977_Automated_daily_pattern_filtering_of_measured_building_performance_data) -- the dataset used in this notebook is identical to that illustrated in the paper.

###A hosted version of the notebook is found [here](http://nbviewer.ipython.org/github/cmiller8/DayFilter/blob/master/DayFilter%20Process.ipynb)

The purpose of `DayFilter` is the automate the process of simply characterizing different day-types accoding to the frequency or infrequency that they occur. Simply separating the *normal* from the *weird*
This dataset is downloadable [here](https://www.dropbox.com/s/30nkwi671ad6lpe/RawData.zip?dl=0) and is licensed under a [Creative Commons Attribution-NonCommercial 3.0 Unported License](http://creativecommons.org/licenses/by-nc/3.0/). 

====================

Background  
----------

If you are unfamiliar with IPython Notebook you can start with http://ipython.org/notebook


Installation  
------------

* Prerequisites  
One of the following distributions is needed. Please note that even if you have Python installed it is important to have one of these distributions installed and the binary for this installation in your path. This is because these distributions come packaged with all the supplementary libraries needed and these have been historically difficult to install separately.

  * EPD Free Enthought Python Distribution from http://enthought.com
  * Anaconda Python from http://continuum.io
  * Development has been done on v 1.5 of Anaconda distribution but EPD Free should work just as well.

* The following steps assume you have installed one of the distributions mentioned in prerequisites.

* From a zip or tar file
    * download the zip or tar file 
    * unpack the file to a directory called learnds
    * cd to the 'notebooks' subdirectory
    * start IPython Notebook 'ipython notebook --pylab=inline'
 
* From the git repo
    * clone the repo
    * cd to 'notebooks'
    * start IPython Notebook 'ipython notebook --pylab=inline'

This work is licensed under a [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/).

