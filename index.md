Workshop Series: Analyzing data and creating a COVID-19 Dashboard from Public Database

### Date and Time: 
March 1st 2022, 2:00 pm EST 

### Location: 
- In person: Health Science Library 

- Virtual : Zoom [link](https://ufl.zoom.us/j/6922131308) | MeetingID : 6922131308

### Instructor Information:
**Name** Natya Hans

**Affiliation** Ph.D. candidate, University of Florida

**Email:** nhans@ufl.edu

Follow me on [Twitter](https://twitter.com/HansNatya)

### Materials 
- Workshop1
Today's workshop slides can be downloaded [here](http://NatyaHans.github.io/Workshops/docs/SARSCoVPresentation.pdf).

# Workshop 1: Downloading SARS-CoV2 data 
- Access the NCBI website through the health science libary Quick links -> Database
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.017.jpeg" alt="Slide17" style="width:90%">

- From the list of databases you can click on NCBI.
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.018.jpeg" alt="Slide18" style="width:90%">

- We land on NCBI homepage, which can be used to submit and download data. If you are interested in developing tools, or learning more about NCBI, there are resources available on the homepage
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.019.jpeg" alt="Slide19" style="width:90%">

- Let's utilize the quick link for SARS-CoV2 data on the top of the home page. 
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.020.jpeg" alt="Slide20" style="width:90%">

-  You can see the records of nucleotide sequences, protein sequences, scientific journals, clinical trial and SRA (Short read archive) information ( as of Feb 25th). Let's click on the nuecleotide records to expand more.
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.021.jpeg" alt="Slide21" style="width:90%">

- We observe that there are more than 4 million nucleotide records available on NCBI. Let's click on the interactive dashboard to see what that looks like
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.022.jpeg" alt="Slide22" style="width:90%">

- We can zoom in to geographic location and filter the sample collection date by weekly, monthly and daily drop down options and the release date by Genbank ( the date when the data became available to download)
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.023.jpeg" alt="Slide23" style="width:90%">

- For example we can narrow in on the samples collected from Florida on a weekly basis and released on weekly basis 
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.024.jpeg" alt="Slide24" style="width:90%">

- Since 4 million records are too many, we are going to download a subset of data which might be more relevant to our research question. We can click on refine results to find these records by several criterias
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.025.jpeg" alt="Slide25" style="width:90%">

- For this tutorial, we are going to focus on complete nucleotide sequences, narrow our search to USA as the geographic location and use lung as the source of sample. But for your own practice and once you are familiar with the tutorial, it might make more sense to download the saliva sample to look for variability.
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.026.jpeg" alt="Slide26" style="width:90%">

- Let's select all of these sequences and click align
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.027.jpeg" alt="Slide27" style="width:90%">

- This is what an alignment looks like, it is color coded for the bases (A,T,C,G). The columns are the position within a single genome and there are 74 genomes which are represented by rows. So each row is a genome. This is a good visualization tool to look for variability between genomes.
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.028.jpeg" alt="Slide28" style="width:90%">

- Now let's build a tree to figure out the evolutionary relationships between these genomes. 
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.029.jpeg" alt="Slide29" style="width:90%">

- What you see now is a phylogenetic tree which depicts evolutionary relationships between individuals. 
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.030.jpeg" alt="Slide30" style="width:90%">

- We can also select what columns need to be displayed in the tabular form. This helps you determine what to download in table. So click on "Select Columns"
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.031.jpeg" alt="Slide31" style="width:90%">

- There are a lot of parameters you can refine by, you can add and remove teh information on the tabular view.
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.032.jpeg" alt="Slide32" style="width:90%">

- Now let's select all the sequences and click download.( Read the next step before you click download)
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.033.jpeg" alt="Slide33" style="width:90%">

- But let's pause because we are downloading sequences in fasta format. What is fasta format?
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentation2.001.jpeg" alt="Slide34" style="width:90%">

- Now that you understand the format, we can begin to download the nucleotide sequence, of the selected record.
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.035.jpeg" alt="Slide35" style="width:90%">

- We can also build a custom definition/header line.
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.036.jpeg" alt="Slide36" style="width:90%">

<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.037.jpeg" alt="Slide37" style="width:90%">
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.038.jpeg" alt="Slide38" style="width:90%">
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.039.jpeg" alt="Slide39" style="width:90%">
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/SARSCoVPresentations.040.jpeg" alt="Slide40" style="width:90%">
# Workshop 1. Downloading Genomic Data from NCBI
- Let's first click on the following [url](https://blast.ncbi.nlm.nih.gov/Blast.cgi) or paste https://blast.ncbi.nlm.nih.gov/Blast.cgi into the browser to get to NCBI BLAST page.

<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/fig1.png" alt="Slide" style="width:90%">

- On the top of this page, we can see resources and shortcuts for SARS-COV2 data. Clicking on it will take you to the following site.

<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/fig2.png" alt="Slide" style="width:90%">

- Let's click on Nucleotides (~4,070,899 Nucleotide records as of Feb, 25th 2022)
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/fig3.png" alt="Slide" style="width:90%">

- You will see several columns with Accession Number, the data Submitter, dates and molecule type etc.  Let's click on Dashboard to get an interactive dashboard with covid-19 data. You can lean in on a specific geographic location, to look at data collection and release dates. We are going to create a similar dashboard in the third part of this workshop series. 
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/fig4.png" alt="Slide" style="width:90%">

- You can also click on the complete tree tab to get details and build phylogenetic tree with all the data.
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/fig6.png" alt="Slide" style="width:90%">

- You can also expand on algorithm and parameters to check the details of how this tree was build. We are going to build a similar tree in second workshop in this series using HiPerGator and RAxML with small number of sequences.
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/fig7.png" alt="Slide" style="width:90%">

- You can also go back and select sequences and use those sequences for building the tree. For simplicity sake, I selected the 38 RefSeq proteins, which have a shortcut available in the Dashboard Visualizations.
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/fig5.png" alt="Slide" style="width:90%">

- Then you can click on Build a phylogentic tree.
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/fig10.png" alt="Slide" style="width:90%">

- You should see a tree with less seqeunces like this.
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/fig9.png" alt="Slide" style="width:90%">

- Now we can select sequences based on several parameters listed here on the right. 



# Workshop 2. Using HiPerGator to build a phylogenetic tree 
The first step is to make a sequence alignment using Alignment software available on HiPerGator.

1. Transfering files from your local computer to HiPerGator:
Tutorial can be found here : [File Transfer](https://natyahans.github.io/posts/2019/04/FileTransferHiPerGator)

2. Making an alignment in phylip format:
Tutorial can be found here : [Clustal Alignment](https://natyahans.github.io/posts/2019/04/FileTransferHiPerGator)

You can then use this alignment file to then build a phylogenetic tree. 

3. Making a phylogenetic tree using RAxML
Tutorial can be found here : [RAxML tutorial](https://natyahans.github.io/posts/2019/05/RunningRAxML/)



# Workshop 3. Workshop on using FlexDashboard in R  
### Pre-requisite
1. Download [R](https://cran.r-project.org/)
2. Download [RStudio](https://www.rstudio.com/products/rstudio/download/#download)
3. Install packages 

- Workshop3
The R markdown for the dashboard can be downloaded [here]().

#### Note for installing packages: 

```
install.packages("PACKAGENAME")
```
Please replace PACKAGENAME by the name of package to download and PACKAGENAME should be within quotes.

For example to download flexdashboard package:

```
install.packages("flexdashboard")
```

### Getting Started
1. For creating a flexdashboard, we first need to create a R markdown document. This is done from RStudio New R Markdown dialog:
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/image1.png" alt="Slide" style="width:90%">

2. Then select from templates flexdashboard and click ok

<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/image2.png" alt="Slide" style="width:90%">

3. Now you should see an Rstudio window that looks like this:
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/image3.png" alt="Slide" style="width:90%">

4. You can see a base flexboard structure. This can be knit by using Knit drop down dialog and clicking on knit to flex_dashboard
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/image4.png" alt="Slide" style="width:90%">

5. After knitting the flexboard structure should appear as follows.
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/image5.png" alt="Slide" style="width:90%">

Now that we know how to make a basic flexdashboard, we can make reports on anything.

### FlexDashboard for SARS-COV2 Data
We need to download additional information from the NCBI database



### Common Errors:
- Required packages are not installed, so please make sure you don't see an error like this (in red). RStudio should give you shortcut on top to install missing packges.
<img src="https://raw.githubusercontent.com/NatyaHans/Workshops/master/Images/image6.png" alt="Slide" style="width:90%">



- For more help, please feel free to contact the Instructor.
- For other tutorials from the Instructor [visit](https://natyahans.github.io/year-archive/)
- For help on flexdashboards and templates [click](https://pkgs.rstudio.com/flexdashboard/)


<!---
**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes
--->
Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/NatyaHans/Blogs/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact
**Name** Natya Hans


