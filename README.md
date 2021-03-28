# sorhum_sap_meta-analysis_mashr
Sorghum association panel meta-analysis - mashr
This repository contains code and data resources to run mashr analysis of Sorghum Association Panel accompanying our research paper
Mural, Ravi V., Marcin Grzybowski, Chenyong Miao, Alyssa Damke, Sirjan Sapkota, Richard E. Boyles, Maria G. Salas Fernandez et al. "Meta-Analysis Identifies Pleiotropic Loci Controlling Phenotypic Trade-offs in Sorghum." bioRxiv https://doi.org/10.1101/2020.10.27.355495.

# docker image
This docker image is built on rocker docker which is a easy way to run codes on rstudo opened on local host after this image is pulled
you can pull this docker image from docker hub as well using below command 

docker pull ravimural/sap_mashr

docker run --rm -p 8787:8787 -e PASSWORD=giveyourpassword ravimuraal/sap_mashr

Open your internet browser and trype "localhost:8787" and enter username as rstudio and password you gave in the above command.

The codes provided corresponds to the mashr analysis using sorghum association panel. Effect size and standard erro of each GWAS results are compiled in single files, datBeta and datSE respectively. These two files serves as initial input files. Description of each step is given along with the codes in the image.

# github repository

