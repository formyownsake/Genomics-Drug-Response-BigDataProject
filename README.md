# Genomics Drug Response
 A Project to predict drug response based on realtime genomics data

 This is a small project to demonstrate Drug Response based on Genomics Data.

 The Data used is from National Center for Biotechnology Information's Genomics Data Generator. 
This data generator generates four types of datasets: 
(1) Microarray data which includes the expression values for a large number of genes for different patients
(2) Patient meta-data which contains the demographic data (patient age, gender, zip code) and clinical information (disease and drug response) for each 
	patient whose genomic data is available in the microarray dataset
(3) Gene meta-data which contains information such as target of the gene (i.e. ID of another gene that is targeted by the protein from the current gene),
	chromosome number, position (number of base pairs from the start of the chromosome to the start of the gene), length (in base pairs) and function (coded as an integer)
(4) Gene Ontology (GO) data which specifies the GO categories for different genes.


Purpose of this Project :

Genomics Data is huge. Can be scaled upto 6-10 TBs per day. Hence Big Data Technology Stack makes it accessible to handle such scale of Data.

Analysis done in this project:
(1) predict the drug response based on gene expressions 
(2) find correlations between expression values of all pairs of genes to find genes which have similar expression patterns and genes which have opposing expression patterns.

The front end application for visualizing the analysis results would be dynamic and interactive based on Flask.