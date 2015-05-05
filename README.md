# SparkR-tutorial-feedback
Feedback on SparkR tutorial

Experiment from this tuto from amplab
https://github.com/amplab-extras/SparkR-pkg/wiki/SparkR-Quick-Start

My config is Ubuntu 14.10 and RStudio

You need to use devtools in order to install some package into R.
JavaR
SparkR

For JavaR, it was ok to install inside RStudio, for SparkR it fails.
Finally it wors on the command line with the cmd install-dev.sh  

It does a lot of thing and may be download a lot of jar more or less compatible with my existing
Spark/Hadoop local install....  

It was OK to run :  

./sparkR examples/pi.R local , which is the classical "Monte-Carlo" computation of PI.

Now , I need to load the package in R (TBD)  

For spark I use simply a standalone install coming from apache foundation
spark-1.3.1-bin-hadoop2.6

Note SparkR will be directly included in Spark V1.4 coming in summer 2015
