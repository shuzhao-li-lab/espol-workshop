# Day 1 schedule

Day 1 focus is overview, metabolomics data preprocessing and preparing for data science tools.

1. Workshop overview, aligning goals and expectations (30 minutes discussion)

  - Understanding of experimental design and statistics
  - Using Jupyter notebooks for data analysis
  - Web tools such as XCMS Online, MetaboAnalyst and Mummichog server
  - Metabolite reporting standards
  - Discussion of research projects

2. Overview of experimental methods and study design in metabolomics, and statistical considerations (60 minutes)

*15 minutes break*

3. Software - MzMine 2, and sample data

[Sample data, human plasma metabolomics, netCDF format, 111 MB]
http://mummichog.org/shuzhao/public/cdf_std_samples_shuzhao_20140709.zip

[MzMine 2]
http://mzmine.github.io/download.html


4. Preparing data science tools - Jupyter notebook

https://jupyter.readthedocs.io/en/latest/content-quickstart.html

Choose one of two ways to run Jupyter notebooks:

1) Using Anaconda, a software distribution for Python/R data science
https://www.anaconda.com/distribution/
After installing, you can use the Jupyter notebook within.

2) Using Docker container.
https://docs.docker.com/get-started/
Docker is not easiest on MS Windows, but it works. After Docker is working, modify this command line to run a Jupyter notebook with a local work directory:
docker run -v /home/shuzhao/project_1_megaID:/home/jovyan/p1 -p 8888:8888 jupyter/scipy-notebook
The directory after "-v" is my working directory, and you should change to yours. That's where the input data file should be, and you will see the mounted directory "p1" via the notebook.


*Lunch break*

5. Participant presentation and discussion (30 minutes)


6. Processing software and the landscape of computational metabolomics (60 minutes)

*15 minutes break*

7. Hand-on session on MzMine 2 and XCMS Online

[MzMine 2 Tutorial at UAB website]
https://www.uab.edu/proteomics/metabolomics/workshop/2018/day2/Hands-on%20analysis%20with%20MZmine%202.pdf

[XCMS Online]
https://xcmsonline.scripps.edu/
Requiring free registration.
