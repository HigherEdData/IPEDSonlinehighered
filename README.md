# Promising or Predatory? Online Education in Non-Profit and For-Profit Universities

### By Christian Smith, Amber Villalobos, Laura Hamilton, and Charlie Eaton

Summary: We use IPEDS and Beginning Postsecondary Students Longitudinal Survey Restricted Datasurvey data to assess the equity implications of the expansion of exclusively online higher education degree programs. 

**Data**
  - IPEDS Online Enrollment
  - IPEDS Fall Enrollment by Race
  - IPEDS Financial Aid and Net Price
  - IPEDS Graduation
  - BPS Derived Student File
  - BPS School Information File

Preanalysis plans are available here: https://osf.io/274we and here: https://osf.io/524va

The repository includes code that:
  - automates the downloading and building of datasets from public IPEDS source data (see .ipynb files starting with c_ in the "Data" director)
  - automates building and merging BPS data files for users with authorized access to BPS restricted access data (see .ipynb files starting with c_ in the "Data" director)
  - Executes and outputs all analyses for tables and figures in the paper.

A preprint of the paper is provided in the main repo directory. You can access the published paper in *Social Forces* here: https://academic.oup.com/sf/advance-article-abstract/doi/10.1093/sf/soad074/7180366

All replication code is in STATA but is provided and executed in Jupyter Notebooks (.ipnynb) using a Stata Kernel. For details see: https://kylebarron.dev/stata_kernel/

If you would like to use the STATA code, you can browse .ipynb NoteBook files in this repository and cut and paste code into your own STATA .do files.

If you would like to edit and execute the .ipynb NoteBook files but do not have Jupyter, you can use the following instructions prepared by Derek Devnich for installing Git, Jupyter, and the STATA Kernel for Jupyter:
* Install Git: https://libguides.ucmerced.edu/software-carpentry/git/install
* Install the Anaconda distribution of Python. This will also install Jupyter Lab: https://libguides.ucmerced.edu/software-carpentry/python/install
* Configure Jupyter Lab to use the STATA kernel: https://libguides.ucmerced.edu/software-carpentry/python/stata
