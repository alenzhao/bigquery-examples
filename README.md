genomics-bigquery
=================

The projects in this repository demonstrate working with genomic data via [Google BigQuery](https://developers.google.com/bigquery/).  All examples are built upon public datasets.  

You can execute these examples by:
 1. Copying and pasting the queries into 
   * the BigQuery [Browser Tool](https://developers.google.com/bigquery/bigquery-browser-tool)
   * the [bq Command-Line Tool](https://developers.google.com/bigquery/bq-command-line-tool)
   * one of the many [third-party tools](https://developers.google.com/bigquery/third-party-tools) that have integrated BigQuery
 1. Running the chunks of R code within the RMarkdown files in [R](http://www.r-project.org/) or [RStudio](http://www.rstudio.com/)
 1. Running the chunks of Python code within the [iPython Notebooks](http://ipython.org/notebook.html) in [iPython](http://ipython.org/)
 
With minor modification, you can run the same analyses on your own genomic data within BigQuery.

Datasets
--------------

### [1000genomes](./1000genomes)
Sample analyses upon VCF data from the [1,000 Genomes Project](http://www.1000genomes.org/)  

**Project Name**: _google.com:biggene_
    
### [pgp](./pgp)
Sample analyses upon the [Personal Genome Project](http://www.personalgenomes.org/)

**Project Name**: _google.com:pgp_

Getting Started
-----------------

 1. Set up a BigQuery project.  
  * Follow the [BigQuery instructions](https://developers.google.com/bigquery/sign-up) on how to sign up for BigQuery and set up a new API project.
  * You can use the Team tab to share a project with other people at your company
  
 1. You’ll need to enable billing and you will be charged for any queries you execute.
  * See BigQuery [pricing](https://developers.google.com/bigquery/pricing) for more detail.
  * For example, queries within the 1,000 Genomes dataset that examine sample genotype columns will process approximately 1TB of data per query. (1,000 GB * $0.005 per GB processed = $5.00)

 1. To add a dataset to your project:
  * go to the BigQuery [Browser Tool](https://developers.google.com/bigquery/bigquery-browser-tool)
  * click on the drop down icon beside your project name in the left navigator
  * pick _‘Switch to project’_ in the menu, and _‘Display project...’_ in the submenu
enter the project name in the _‘Add Project’_ dialog.


Contributing changes
--------------------

See [CONTRIB](CONTRIB.rst).

Licensing
---------

See [LICENSE](LICENSE).