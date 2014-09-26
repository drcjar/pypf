pypf
====

 IPF epidemiology with python
 
 Notebooks may be viewed with nbviewer here 
 
 http://nbviewer.ipython.org/github/drcjar/pypf/tree/master/notebooks/

quick start reproducible science
===

 1. git clone https://github.com/drcjar/pypf.git
 2. virtualenv pypf-virtualenv
 3. cd pypf-virtualenv
 4. source bin/activate
 5. pip install -r requirements.txt
 6. pip install matplotlib==1.3.1
 7. pip install statsmodels==0.5.0
 8. cd pypf notebooks
 9. ipython notebook –pylab=inline
 10. pypf prepares death data
 11. pypop prepares population data
 12. pypf_prep prepares a standard 2008 ref population
 13. pypf_analysis makes pictures
 14. pypf_poisson does a poisson analysis
 15. pypf_maps makes maps
 
n.b if none of the above makes much sense to you then http://learnpythonthehardway.org/book/ and  https://dont-be-afraid-to-commit.readthedocs.org/en/latest/ aren't bad places to start :-)
