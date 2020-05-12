# TCGA

## 1. introduction

TCGA is largest cancer database, we could download lots of cancer data here.

It has plenty of __clinal__ data.


## 2. download data

1. https://portal.gdc.cancer.gov/

2. __exploration__: choose cancer type and details
	__view in repository__: choose _FILES_ to select data type

3. add to cart:

please download:

__Metadata__: Samples information: file_name, file_id, platform, datatype...

__Clinical__: clinical information, like Diagnosis, treatment, ages, cancer stage ....

__Manifest__: data annotation, a few columns including file_id, file_name, MD5, size, state

__Cart__: genes data



## or you could also use gdc-client to download data

gdc-client download -m manifest.txt



