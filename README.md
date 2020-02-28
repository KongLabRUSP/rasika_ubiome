##  Project: Gut Microbime Role in Diallyl Sulfide (DAS) Inhibiting NNK-Induced Cancer in A/J Mice Model
### Study ID: 
### Scientist: Rasika Hudlikar
### Data Analysis: Davit Sargsyan 
### Created: 02/25/2020

---    

## Table of Contents
[Study Design](#dsgn)
[Daily Logs](#logs)  
[Results](#results)   
[Files](#files)
[References](#ref)   

## Study Design<a name="dsgn"></a>
A/J inbred mice from the Jackson Laboratory are used to model cancer and for carcinogen testing given their high susceptibility to carcinogen-induced tumors.  
  
From [Cayman Chemical](https://www.caymanchem.com/product/20894/diallyl-sulfide):Diallyl sulfide is a thioether found in garlic that can modulate the cytochrome P450 drug metabolizing system, activate the constitutive androstane receptor to regulate multidrug resistance-associated proteins, and upregulate the expression of detoxifying enzymes. Garlic-derived organosulfides such as diallyl sulfide have been shown to be highly protective from chemically-induced carcinogenesis in animals.  
  
Nicotine-derived nitrosamine ketone (NNK) is one of the key tobacco-specific nitrosamines derived from nicotine. It plays an important role in carcinogenesis.  
  
Nine (9) A/J mice were used in this study, 3 in each of the 3 treatment groups: Vehicle control (VC), NNK control and NNK+DAS. The study design is as follows:  
![](docs/aj_mice_nnk_study _design.png)  
  
DAS in corn oil was force-fed to mice throghout the study (weeks 0 to 6). A single dose of 24uM/0.1mL NNK suspended in glyceryl trioctate vehicle was injected at Week 1 intraperetoneally (IP). The vehicvle control group received vehicle only. Fecal samples were collected at 4 timepoints: before DAS treatment began (Week 0), and 1, 2 and 4 weeks after pretreatment (Week 1, Week 2 and Week 4 respectively).  

## Daily Logs<a name="logs"></a>
### 02/25/2020
* FastQ files downloaded from [Rutgers Box](https://rutgers.app.box.com/folder/99758165982).  
  
### 02/27/2020
**Notes from the lab meeting:**       
1. Meta-data received from Rasika  
2. FastQ files processed with a DADA2 script

## Files<a name="files"></a>
1. ***fastq_jan2020*** folder contains 72 FastQ files (36 pair-ended samples).     
2. ***data/16s samples from AJ mice expt.xlsx***: meta-data.    

## References<a name="ref"></a>
1. [DADA2 Pipeline Tutorial on GitHub, Benjamin Callahan](https://benjjneb.github.io/dada2/tutorial.html)
2. [Change Window 7 virtual memory Size](https://support.lenovo.com/us/en/solutions/HT002951)
3. [Rutgers On-Demand High Power computing](https://ondemand.hpc.rutgers.edu), run RStudio server (specify number of cores)