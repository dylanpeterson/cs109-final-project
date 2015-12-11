# SNP Analysis of 3000 Rice Genomes
### Dylan Peterson, O'Neil Danis, and Eric Slater

#### Overview
In this project, we used multiple statistical models to make predictions about if a rice strain matures faster based on Single Nucleotide Polymorphisms (SNPs) and phenotypic features. SNPs were obtained from the AWS 3k Rice Genome project, hosted on s3, which contained multiple data files. One of which was a set of 990,009 SNPs for the 3k strains that were compared against a reference genome. This data was used in combination with phenotypic data from the International Rice Genebank Collection Information System.

####Project Notebook
Our project notebook can be found in the master branch of our repository. The name of the notebook is processbook.ipynb.

####Non-Standard Python Libraries and other Programs Used
PyVCF was downloaded from https://pypi.python.org/pypi/PyVCF/0.6.0 and added to Python libraries by running the setup.py file. The library can be imported by `import vcf`. This packaged is used to work with a VCF file (which contains SNP data) in our processbook.

We used plink 1.9 (can be downloaded at https://www.cog-genomics.org/plink2) to convert PED and MAP files into a VCF file with the terminal command `command: ./plink --file tempdata/NB-core_v4 --recode vcf`. This was done to make the data in a format compatible with the PyVCF package.

#### Large Data Saved in Dropbox
A lot of our data was too large (200 MB to 12 GB) to include in our Github repository, so we saved much of it in this Dropbox link: https://www.dropbox.com/sh/7dglv10l515k335/AADo7kA8jVmxspsYud3Ft1y_a?dl=0

#### Project Website
Our project website can be accessed at this URL:  http://dylanpeterson.github.io/cs109-final-project

#### Project Screencast Video
Our project screencast video can be accessed at this URL:

#### Old Project Repository
Our project began in an earlier repo, accessible at this URL: https://github.com/o0neil/Believe_The_Hype
