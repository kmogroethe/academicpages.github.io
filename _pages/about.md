---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello, nice of you to stop by! I am an infectious disease epidemiologist interested in how molecular epidemiology and new technologies can assist infectious disease research and public health surveillance (both domestically and abroad).
<br />

Quick Summary: Research Interests & Skills
======

Molecular and genomic epidemiology, population health, population genetics of infectious disease organisms, data-driven approaches for public health solutions, integration of novel technologies and datasets (next generation sequencing; demographic health surveys, big data) with traditional epidemiologic approaches; development of bioinformatic resources for various public health purposes 

* **Analysis of large surveillance data sets** (Malaria Indicator Surveys, Demographic Health Surveys, FDA Adverse Reporting System)

* **Statistical analyses for epidemiological and genomic data**, including mixed effects regression models for longitudinally collected and clustered data, and machine learning techniques (random forests, k-means clustering, etc.)

* **De novo assembly and variant identification pipelines** for next/third generation sequencing platforms (Illumina, PacBio, Oxford Nanopore)

* **Data analysis and visualization** of epidemiological and genomic data sets with: **R/R Shiny, SAS, Perl, Python, Bash, Linux/Unix**
<br />

Whole genome sequencing: the good, the bad, and the ugly
======

The breakneck pace of sequencing technology development has left in its wake a vast resource of genetic and genomic data, currently totaling multiple petabases of sequence. As infectious disease researchers incorporate sequencing technologies into new fields and pathogens, we observe rapid accumulation of this data - here's the amount of sequencing data (in base pairs) accumulating for <i>Plasmodium</i> spp. since the publication of the *P. falciparum* reference genome up to last year:

<img src="images/seq-trends.png" alt="hi" class="inline"/>

While this information can be incredibly helpful in disease research and surveillance, the enormous scale of available sequences (and required resources for analysis) present daunting challenges on how to efficiently incorporate these data into sound epidemiologic studies. A new generation of public health researchers, trained in both epidemiology and bioinformatics, is essential to 21st century disease research to track the emergence of drug resistance, inform vaccine design, and assess the impact of interventions on pathogen populations. 
<br />

Research Activities
======

### Genomic Epidemiology of Malaria

My research has shown just how useful high-throughput genetic and genomic tools can be for exploring these issues. My dissertation work at the Institute for Genome Sciences (University of Maryland School of Medicine) under [Dr. Joana Silva](http://www.medschool.umaryland.edu/profiles/Carneiro-da-Silva-Joana/) and [Dr. Christover V. Plowe](https://globalhealth.duke.edu/people/faculty/plowe-christopher) focused on how molecular epidemiology and population genomics can inform the design of whole-organism malaria vaccines and aid in the interpretation of clinical trials. While whole-organism vaccines appear to offer high protection (90-100%) against malaria parasites that look like the vaccine strain, efficacy is lower against non-vaccine strains (~40-80%), suggesting that the well-established genetic diversity of this parasite hampers our ability to design effective vaccines. Multi-strain or region-specific vaccines may help improve vaccine efficacy. However, a limited amount of strains that can be adapted for vaccination purposes are available, and it is critical that that we understand how these strains differ both at the genomic and genetic level before selecting additional vaccine strains. 

###### <i>P. falciparum</i> PacBio assemblies for vaccine (NF54) and heterologous CHMI strains, compared to the 3D7 reference genome
<img src="images/assemblies.png" alt="hi" class="inline"/>

Using both long and short read platforms, we gererated <i>de novo</i> assemblies for strains used for vaccination and controlled human malaria challange purposes, and used these assemblies to conduct a rigorous characterization of each strain, documenting thousands of differences between strains that may impact immune recognition. The [high-quality assemblies](https://genomemedicine.biomedcentral.com/articles/10.1186/s13073-019-0708-9) generated through this research have allowed not only for throughough genomic and genetic characterization of these strains, but also reveal information on structurval variants, which have previously been difficult to directly detect with short-read technologies

While whole genome sequencing technologies are great for generating as much data as possible and discovering new variants, limits on cost and low-DNA samples restrict the use of this technology for all samples. I am currently a Postdoctoral Fellow at the University of North Carolina Chapel Hill working in the Infectious Disease Epidemiology and Ecology Lab [(IDEEL)](https://www.med.unc.edu/infdis/ideel/), where we are exploring how molecular inversion probes (MIPs) can allow for targeted and efficient genotyping at lower cost compared to whole genome sequencing. MIPing samples from sub-Saharan Africa from our group have shown that this technology can also reveal population structure between and within countries, allowing a more affordable way for National Control Programs to monitor parasite population changes as interventions are rolled out.

### Don't forget about the vectors

I also have several projects related to vector genomics and vector surveys. In addition to using genomic tools to better understand vector phenotypes linked to behavoir or insecticide resistance, vectors potentially are a unique tool to monitor pathogen populations. Genotyping malaria parasites directly from the <i>Anopholes</i> mosquito host would capture a more thourough picture of circulating malaria parasites that could infect humans. In addition, many mosquitoes species are capable of transmitting a wide variety of pathogens between human and non-human hosts. Understanding the full pathogen reservoir contained in such vectors is important for understanding transmission risks for human populations. Ongoing projects include suveys of <i>Plasmodium</i> spp. from <i>Anopholes</i> in the DRC, viral metagenomic projects for <i>Aedes aegytpi</i> (also from the DRC), the generation of an assembly for an <i>A. aegypti</i> strain captured from Miami Beach as part of ongoing surviellence for Zika oubreaks, and a study investigating genetic variants associated with pyrethroid resistance in <i>Aedes</i> and <i>Culex</i> species from North Carolina counties which contain varying intervention and selective pressures.

###### Mosquito collections outside of Kinshasa, DRC
<img src="images/kmoser-mozzie.jpg" alt="hi" class="inline"/>

### Capacity building

The large amount of sequencing data, while often stored on open-access platforms, is not truly accessible to many infectious disease researchers, particularly those who come from resource-limited settings (both domestically and internationally). Barriers for accessing this information may be computational or hardware-related in nature, or can also be from a lack of available training opportunities. Identifying a minimum key set of computational resources on which genomic analyses can be run and training public health officials to analyze sequencing data will benefit infectious disease research worldwide, and is something I hope to make a major componant of my career. Most recently, I have assisted in a one-day Parasite Genomics workshop in Lusaka, Zambia, organized through the South Africa International Centers for Excellence for Malaria Research (ICEMR) program with Johns Hopkins University, Purdue University, and the University of North Carolina Chapel Hill. Participants were given introductory lectures to genotyping laboratory methods, population genetic concepts, and spatial epidemiology methods using genetic data, followed by a hands-on componant analysing data in R. Planning for longer follow-up workshops, where participants will bring their own data to analyse over the course of a week, are in the works!

###### Dr. William Moss of JHU hands out certificates of completion to the particpants of the joint JHU/UNC/Purdue Parasite Genomics Workshop at the National Malaria Elimination Center in Lusaka, Zambia  
<img src="images/IMG_20190321_162859.jpg" alt="hi" class="inline"/>

### Antibiotic resistance and small-scale poultry farming

During my MPH studies at the University of Michigan, I worked in [Dr. Joseph Eisenberg's](https://sph.umich.edu/faculty-profiles/eisenberg-joseph.html) group utilizing DNA microarray platforms to detect mobile genetic elements (such as integrons and plasmids) in <i>E. coli</i> isolates from Ecuadorean birds and humans associated with small-scale production farming operations (which utilize antibiotics in poultry feed), and incorporated these data into mixed effects models to assess the impact of these practices on drug resistance in the surrounding community. Our results show not only higher levels of phenotypic resistance and genetic mobile elements in small-scale production birds compared to free-range birds, but also higher levels of genetic mobile elements and related phenotypic resistance profiles in humans associated with small-scale production birds compared to humans associated with free-range birds. These small-scale operations in developing nations, which typically house less than 100 birds per coop, appear to be more than capable of becoming a reservoir of antibiotic resistance for the humans who interact with them, and that the phenomenona of high resistance levels in livestock is not just restricted to the large-scale operations we are familiar with in the United States. [These results](https://doi.org/10.1093/aje/kwx286) have important implications for public health and policy, as small-scale production farming is increasingly viewed as [a tool for economic development](https://www.gatesnotes.com/Development/Why-I-Would-Raise-Chickens).
