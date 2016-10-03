---
title: Software Tools
layout: default
---

## 1. Glossary for Software Tools

### 1-1. Software type

  * **Stand-alone software**  
    Software that is downloaded and installed on a computer.
    
  * **Web application**  
    Application accessed and used using a web browser.
    
  * **Web service**  
    Application invoked over the internet by computational means. It accepts machine readable data and provides remachine readable data as result.

### 1-2. Data types

  * **MS**  
  Mass spectrometric data

## 2. Software Tools

### 2-1. GRITS Toolbox
  GRITS Toolbox is a glycomics MS data processing software. The software allows not just to load, visualize and browser glycomics MS data but also to annotate the data with glycan structures and their fragments. Automatic annotated data can be manually evaluated, changed and exported to Excel. In addition side by side comparison of the different experiment for the study of glycosylation changes and glycosylation expression changes can be performed as well. In addition the software also captures and manages meta data such as sample description and description of the performed experiment.

| | |
---|---
**Processed Data** | MS
**Software Type** | Standalone Software
**Availabitlity** | http://www.grits-toolbox.org/
**License** | none
**Status** | stable, continues development
**Funding** | NIH
**Future Plans** | quantification of glycomics data; CMS like methods for glycomics; integration of other data types, such as qRT-PCR
**Contact** | Rene Ranzinger: rene@ccrc.uga.edu


### 2-2. GODESS
  NMR spectrum simulation service for carbohydrate-containing molecules (including polymers and glycoconjugates). The output includes signal assignment tables, 1D and multiple 2D spectra. For every simulated chemical shift the predictor reports the expected error, trustworthiness metrics and databases references to data used in the simulation. The software uses empirical approach with own dedicated databases, statistical approach based on CSDB content, and hybrid approach. Supported nuclei are 13C and 1H. Solvent and temperature are taken into account. On the level of structures it supports most structural features of saccharides (several hundred residues, alditols, furanoses, amino acids, fatty acids, sphingoids; glycosidic, amide, or diester linkages). Average accuracy obtained on a large pool of structures was 0.86 ppm for &sup1;&sup3;C and 0.07ppm for &sup1;H.
 
| | |
---|---
**Processed Data** | NMR, structures
**Software Type** | web application
**Availabitlity** | http://csdb.glycoscience.ru/database/core/nmrsim.html
**License** | none (free)
**Status** | stable, continues development
**Funding** | Russiann Foundation for Basic Research
**Future Plans** | HMBC prediction, structure iterator & ranking
**Contact** | Phyl Toukach: netbox@toukach.ru


### 2-3. GlycoDigest
  GlycoDigest is a tool that simulates the action of exoglycosidases on released oligosaccharides. It has been developed to assist glycobiologists design mixtures of exoglycosidases that can be used to guide the precise determination of glycan structures.
 
| | |
---|---
**Processed Data** | glycan structures
**Software Type** | Standalone software and integrated in GlycoBase and UniCarbKB
**Availabitlity** | http://www.glycodigest.org
**License** | CC
**Status** | stable, continues development
**Funding** | SIB; National eResearch Collaboration Tools and Resources (NeCTAR) Project
**Future Plans** | Extend range of enzymes for simulation of activity; budding plan with CAZy team.
**Contact** | Matthew Campbell:matthew.campbell@mq.edu.au<br>Frederique Lisacek: frederique.lisacek@isb-sib.ch


### 2-4. 3D structure validation tools (CARP, pdb-care)
Tools for validation of carbohydrate 3D structure data.

| | |
---|---
**Processed Data** | PDB-formatted 3D structures (carbohydrates, glycoproteins, protein-carbohydrate complexes)
**Software Type** | Web application, Integrated in Glycosciences.de
**Availabitlity** | http://www.glycosciences.de/tools/
**License** | 
**Status** | stable, continues development
**Funding** | -
**Future Plans** | Include MonosaccharideDB routines for improved handling of modified residues.
**Contact** | Thomas Lütteke: thomas.luetteke@vetmed.uni-giessen.de


### 2-5. Sweet-II
Building of 3D structure models of carbohydrates.

| | |
---|---
**Processed Data** | carbohydrate “sequence” (2D-structure)
**Software Type** | Web application, Integrated in Glycosciences.de
**Availabitlity** | http://www.glycosciences.de/modeling/sweet2/
**License** | 
**Status** | stable
**Funding** | -
**Future Plans** | -
**Contact** | Thomas Lütteke: thomas.luetteke@vetmed.uni-giessen.de


### 2-6. GlyProt
In-silico glycosylation of protein 3D structures.

| | |
---|---
**Processed Data** | Protein 3D structure (PDB format), carbohydrate “sequence” (2D-structure)
**Software Type** | Web application, Integrated in Glycosciences.de
**Availabitlity** | http://www.glycosciences.de/modeling/glyprot/
**License** | 
**Status** | stable
**Funding** | -
**Future Plans** | -
**Contact** | Thomas Lütteke: thomas.luetteke@vetmed.uni-giessen.de


### 2-7. ISOGlyP (Isoform Specific O-Glycosylation Prediction)
  ISOGlyP  analizes and roughly predicts isoform specific sites of mucin O-glycosylation for an entered protein sequence .  Future goals are to add the long range enhancing effects of remote O-glycosylation and the action of multiple transferases.  This work is being performed by a collaboration of Thomas Gerken at Case Western Reserve Univ. (School of Medicine) and  Ming-Ying Leung at the Univ. Texas at El Paso (Professor of Mathematical Sci. and Director Bioinformatics Program).  The Gerken  lab is generating the actual data utilizing a series of unique random (glyco)peptides (refs below) and the Leung lab has developed the web site.  We presently have the peptide sequence motif/propensity data for 10 of the 20 isoforms on the site and have generated the remote glycopeptide data on ~11 isoforms (not yet on the site).  We also have plans for developing similar approaches to predict the Core 1, Core 3 and sialylation substitution of the peptide GalNAc by similar methods.

| | |
---|---
**Processed Data** | FASTA format protein sequence (manual or file input)
**Software Type** | Web application
**Availabitlity** | http://isoglyp.utep.edu/
**License** | none
**Status** | available, under development
**Funding** | NIH (data acquisition and web site 1/2015-11/2018)
**Future Plans** | include remote glycosylation with improved output graphics, add core 1 & 3 and sialylation predictions
**Contact** | T. Gerken: txg2@cwru.edu Tel: 216-368-4556<br>M. Y. Leung: mleung@utep.edu Tel: 915-747-6836

References:
Perrine et al (2009) http://glycob.oxfordjournals.org/content/19/3/321
Gerken et al. (2011) http://www.jbc.org/content/286/16/14493
Gerken et al  (2013) http://www.jbc.org/content/288/27/19900
Kong et al (2015)    http://glycob.oxfordjournals.org/content/25/1/55.abstract


### 2-8. GlycReSoft  (1)
  GlyReSoft is a modular software tool for assigning site specific glycosylation from bottom-up mass spectrometry data sets.  The tool accepts LC-MS data from any vendor converted into public data formats and contains modules for following tasks:
  
  *  Assigning and scoring glycomics LC-MS profiling data.
  
  *  Calculating glycopeptide search space size informed by glycomics and proteomics information.
  
  *  Assigning and scoring glycan and glycopeptide MS and tandem mass spectra.
  
  *  Calculating false discovery rates from glycopeptide search spaces constructed using glycomics and proteomics data.

| | |
---|---
**Processed Data** | Spectrometry data
**Software Type** | Stand-alone and Web application
**Availabitlity** | https://github.com/GlycReSoft2
**License** | Tentatively Apache2, but always free for academic use
**Status** | Available, Under Development
**Funding** | 
**Future Plans** | 
**Contact** | Joseph Zaia: jzaia@bu.edu

References: 
Maxwell, E., Tan, Y., Tan, Y., Hu, H., Benson, G., Aizikov, K., Conley, S., Staples, G. O., Slysz, G. W., Smith, R. D., and Zaia, J. (2012) GlycReSoft:A Software Package for Automated Recognition of Glycans from LC/MS Data. PLoS ONE 7, e45474


### 2-9. HS-SEQ (2)
HS-SEQ is a comprehensive algorithm for sequencing of glycosaminoglycan saccharides from activated electron dissociation (ExD) tandem mass spectra. ExD methods encompass ion electron detachment dissociation (EDD) and negative electron transfer dissociation (nETD).

| | |
---|---
**Processed Data** | 
**Software Type** | Stand-alone
**Availabitlity** | https://github.com/hh1985/glycan-pipeline
**License** | 
**Status** | 
**Funding** | 
**Future Plans** | 
**Contact** | Joseph Zaia: jzaia@bu.edu

References:
Hu, H., Huang, Y., Mao, Y., Yu, X., Xu, Y., Liu, J., Zong, C., Boons, G. J., Lin, C., Xia, Y., and Zaia, J. (2014) A Computational Framework for Heparan Sulfate Sequencing Using High-resolution Tandem Mass Spectra. Molecular & cellular proteomics : MCP 13, 2490-2502


### 2-10. GlyPy
GlyPy is a modular and extensible library of glycan manipulation tools built in python with minimal dependencies.   This library is available for researchers as a resource to solve glyco-bioinformatics problems.  All that is required is a minimal knowledge of the general purpose, high level, python programming language. Designed for both batch processing and interactive use.
The library includes the following functions:

  * Read and write condensed GlycoCT, GlycoMinds Linear Code, IUPAC Linear Code, and read GlycoCT XML glycan structures
  
  * Calculate structure masses from monoisotopic or average composition, under theoretical neutral charge or under any charge state.
  
  * Build and modify glycan structures dynamically, with reverse-ability maintained wherever possible, adding or removing modifications, substituents, monosaccharides or other glycans to the graph structure.
  
  * Interact with glycan structures using natural pythonic expressions, providing a rich iterative interface for transforming graphs.
  
  * Generate fragments of glycan structures by cleaving one or more glycosidic bonds. Can generate A, B, C, X, Y and Z ions, as well as internal fragments
  
  * Derivatize glycan structures with arbitrary substituents.
  
  * CFG-style plots with colored shapes or IUPAC text for nodes.
  
  * GlycomeDB API and partial support for the recently exposed glySpace REST API
  
  * Self-documenting with Sphinx
  
  * Near 100% test coverage on the core library
  
  * Build portable databases of structures, indexed for fast search and retrieval.
  
  * Define new types of substituents and modifications as needed.

| | |
---|---
**Processed Data** | 
**Software Type** | Software Library
**Availabitlity** | https://github.com/mobiusklein/glypy
**License** | Tentatively Apache2, but always free for academic use
**Status** | Available, Under Active Development (Feature Requests and Pull Requests Welcome)
**Funding** | 
**Future Plans** | Continued development of glycan structure model and algorithms on that model.
**Contact** | Joseph Zaia: jzaia@bu.edu
