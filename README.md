# OTML_Statlearn2018

Courses and practical sessions for the Optimal Transport and Machine learning course at [Statlearn 2018](http://statlearn.sfds.asso.fr/).


This course has been prepared by [Rémi Flamary](http://remi.flamary.com/)  and [Nicolas Courty](http://people.irisa.fr/Nicolas.Courty/).

### Course

* Introduction to Optimal Transport [[PDF]](https://remi.flamary.com/cours/otml/OTML_Statlearn_2018_OTintro.pdf)
    * Optimization problem
    * Regularization
* OT for Machine Learning [[PDF]](https://remi.flamary.com/cours/otml/OTML_Statlearn_2018.pdf)
    * Mapping with Optimal Transport
    * Learning from histograms with Wasserstein distance
    * Learning from empirical distributions with Wasserstein distance


### Practical Sessions


#### Install Python and POT Toolbox

In order to do the practical sessions you need to have a working Python installation. 
The simplest way on any OS is to install the [Anaconda](https://www.anaconda.com/download/) distribution that can be freely downloaded from [here](https://www.anaconda.com/download/).

When anaconda is installed the simplest way to install pot is to launch the anaconda terminal and execute:

```
conda install -c conda-forge pot 
```

which will install the POT OT Toolbox automatically.

#### Download the Notebooks for the session

You can download all the necessary files here: [OTML_Statlearn2018.zip](https://github.com/rflamary/OTML_Statlearn2018/archive/master.zip)

The zip file contains the following session:

0. [Introduction to OT with POT](0_Intro_OT.ipynb)
1. [Domain adaptation on digits with OT](1_DomainAdaptation.ipynb)
2. [Color Grading with OT](2_ColorGrading.ipynb)

You can choose to do the practical session using the notebooks included or the python script. We recommend Notebooks for beginners. 

The solutions  for the practical sessions can be obtained ath the following URL:

```
https://remi.flamary.com/cours/otml/solution_[NUMBER].zip
```

Where [NUMBER] has to be replaced by the integer part of the value of the Wasserstein obtained in Practical [Session 0](0_Intro_OT.ipynb) with the Manhattan/Cityblock ground metric.
