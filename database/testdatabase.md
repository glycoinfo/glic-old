---
title: Database Resources
layout: databasescroll
---

<a name="glossary1">  

<br>  

##  1. Glossary for Database Resources  

### 1-1. Data  
  * **Structure**  
  Structure of a molecule represented in one or several sequence formats or graphicalrepresentation.  
  
  * **Database reference**  
  References to other databases of the same type containing the same molecule.
  
  * **Species annotation**  
  Biological annotation describing the species the structure is found.

### 1-2. Search options  
  * **Structure search**  
  Allows searching for a structure by specifying is sequence.
  
  * **Sub-structure search**  
  Search for structure based on a query structure that is a substructure of the structures in the search result.
  
  * **Maximum common substructure search (MCS)**  
  Search of structures based on shared substructures with the query structure. The less query structure and another structure have in common the lower the score. If query structure and queried structure are identical or the query structure is subsumed by the other structure the score is maximum.
  
  * **Similarity search**  
  Search structures that are similar to a query structure. This search is different to the sub-structure search or the MCS search those residues and linkages may vary between the query and result structure.
  
  * **Search by species**  
  Search of structures based on their species annotation. This may allow for searches by higher species organization, such as Genus, Rank or Kingdoms.
  
<br>
  <a name="data2"> 
 
<br>  
<br>  

## 2. Database Resources

### 2-1. GlycomeDB<a name="data21">
  Meta database that integrates the structures from several glycomics databases (CFG, KEGG, GLYCOSCIENCES.de, GlycoBase, JCGGDB, BCSDB, PDB, GlycO and Carbbank) into one consistent sequence representation and creating a unique index of all structures present in the integrated database. Species annotations from the other databases are retrieved as well and integrated using the NCBI Taxonomy. Each structure in GlycomeDB is linked back to the original database allowing finding and browsing all occurrences of a structure in multiple databases.

| | |
---|---
**Data in Database** | structure, databases references, species annotation
**Search Options** | structure search, sub-structure search, similarity search, maximum common substructure search, species search
**Availability** | <http://www.glycome-db.org>
**License** | None
**Status** | stable, maintained
**Funding** | -
**Future Plans** | -
**Code Availablity** | on request
**Contact** | Rene Ranzinger: <rene@ccrc.uga.edu>

<br>  
<a name="data22">
<br>  
<br>  

### 2-2. UniCarbKB
  The UniCarb KnowledgeBase (UniCarbKB) offers public access to a growing, curated database of information on the glycan structures of glycoproteins. UniCarbKB is an international effort that aims to further our understanding of structures, pathways and networks involved in glycosylation and glyco-mediated processes by integrating structural, experimental and functional glycoscience information. This initiative builds upon the success of the glycan structure database GlycoSuiteDB, together with the informatic standards introduced by EUROCarbDB, to provide a high-quality and updated resource to support glycomics and glycoproteomics research. UniCarbKB provides comprehensive information concerning glycan structures, and published glycoprotein information including global and site-specific attachment information.
  
| | |
---|---
**Data in Database** | structure, glycoproteins, site-specific information, databases references, species annotation, tissue, cell line, biological fluid, methods
**Search Options** | structure search, sub-structure search, species search, glycoprotein search, UniProtKB accession number search, tissue search, composition search
**Availability** | <http://unicarbkb.org>
**License** | CC
**Status** | stable, maintained
**Funding** | The National eResearch Collaboration Tools and Resources (NeCTAR) Project; Swiss National Science Foundation
**Future Plans** | Continued curation, better integration and support for GlycoRDF, improved search and query functionality
**Code Availablity** | Release 1 GitHub public, On-going developments BitBucket user managed
**Contact** | -

<br>

### 2-3. Carbohydrate Structure Database (CSDB)<a name="data23">
  The Carbohydrate Structure Databases (CSDBs) store structural, bibliographic, taxonomic, NMR spectroscopic, and other data on natural carbohydrates and their derivatives published in the scientific literature. The CSDB project was launched in 2005 for bacterial saccharides (as BCSDB). Currently, it includes two parts, the Bacterial CSDB and the Plant&Fungal CSDB. In March 2015, these databases were merged to the single Carbohydrate Structure Database (CSDB). The combined CSDB includes information on bacterial and archaeal glycans and derivatives (the coverage is close to complete), as well as on plant and fungal glycans and glycoconjugates (almost all structures published up to 1998). CSDB is regularly updated via manual expert annotation of original publications. Both newly annotated data and data imported from other databases are manually curated. The CSDB data are exportable in a number of modern formats, such as GlycoRDF. CSDB provides additional services for simulation of 1H, 13C and 2D NMR spectra of saccharides, NMR-based structure prediction, glycan-based taxon clustering, and other.
  
| | |
---|---
**Data in Database** | structures, NMR spectra, taxon annotations, bibliographic annatations, databases references, supplementary data
**Search Options** | structure search, sub-structure search, composition search, taxon search, bibliography search, NMR signal search, id search
**Availability** | <http://csdb.glycoscience.ru>
**License** | None (free)
**Status** | stable, maintained
**Funding** | Russian Foundation for Basic Research
**Future Plans** | see papers
**Code Availablity** | no
**Contact** | Phyl Toukach: <netbox@toukach.ru>

<br>

### 2-4. SugarBindDB<a name="data24">
The SugarBind Database (SugarBindDB) covers knowledge of glycan binding of human pathogen lectins and adhesins. It is a curated database; each glycan-binding event is associated with at least one published reference. The core data of SugarBindDB is a triple constituted of a pathogenic agent, a lectin/adhesin and a glycan ligand. SugarBindDB content is displayed in views. All views are interconnected.

| | |
---|---
**Data in Database** | structure, pathogenic lectin/adhesin, protein-carbohydrate interactions, cross-references, binding annotation, tissue, disease, symptoms, methods
**Search Options** | species search, lectin search, ligand search, tissue search, disease search, multi-criteria search
**Availability** | <http://sugarbind.expasy.org>
**License** | CC
**Status** | stable, maintained
**Funding** | SIB Swiss Institute of Bioinformatics + Swiss National Fund
**Future Plans** | increased data integration, continued data curation, addition of binding prediction tools
**Code Availablity** | <https://bitbucket.org/sib-pig/sugarbind>
**Contact** | -

<br>

### 2-5. Glycosciences.DB<a name="data25">
  Database of the Glycosciences.de portal. Contains CarbBank structures + PDB carbohydrates + structures with NMR shifts extracted from the literature.
  
| | |
---|---
**Data in Database** | structure, 3D structure models, pdb data, nmr shifts, species annotation, literature references
**Search Options** | structure search, sub-structure search, motif search, n-glycan properties search, literature search, nmr peak search
**Availability** | <http://www.glycosciences.de/database>
**License** | None
**Status** | stable, maintained
**Funding** | -
**Future Plans** | -
**Code Availablity** | -
**Contact** | Thomas Lütteke: <thomas.luetteke@vetmed.uni-giessen.de>

<br>

### 2-6. MonosaccharideDB<a name="data26">
  Monosaccharide database. Contains monosaccharides + name parsing / encoding routines.
  
| | |
---|---
**Data in Database** | monosaccharide properties, residue names
**Search Options** | name search, properties search
**Availability** | <http://www.mononsaccharidedb.org>
**License** | -
**Status** | stable, maintained
**Funding** | -
**Future Plans** | -
**Code Availablity** | -
**Contact** | Thomas Lütteke: <thomas.luetteke@vetmed.uni-giessen.de>

<br>

### 2-7. GlycoMapsDB<a name="data27"> 
  Database of conformational maps of glycosidic linkages

| | |
---|---
**Data in Database** | conformational maps derived from MD simulations
**Search Options** | disaccharide search
**Availability** | <http://www.glycosciences.de/modeling/glycomapsdb>
**License** | -
**Status** | stable
**Funding** | -
**Future Plans** | -
**Code Availablity** | -
**Contact** | Thomas Lütteke: <thomas.luetteke@vetmed.uni-giessen.de>

<br>

### 2-8. GlyTouCan<a name="data28">
  Glycan structure/sequence/composition repository
  
| | |
---|---
**Data in Database** | Glycan structures, as images, GlycoCT and WURCS, and their motifs, monosaccharides and linked to other related databases including GlycomeDB, BCSDB, GlycoEpitope, with others continuing to be added. Each glycan structure is assigned a GlyTouCan ID.
**Search Options** | Graphical and textual substructure search, ID search and motif search
**Availability** | <http://www.glytoucan.org>
**License** | CC-BY
**Status** | stable, maintained
**Funding** | Integrated Database Project of Japan
**Future Plans** | Incorporation of UniCarbKB and other JCGGDB databases
**Code Availablity** | open source
**Contact** | Kiyoko F. Aoki-Kinoshita: <kkiyoko@soka.ac.jp>

<br>

### 2-9. GlycoPattern<a name="data29">
  GlycoPattern is Web-based bioinformatics resource to
support the analysis of glycan array data for the Consortium for Functional Glycomics. This resource includes algorithms and tools to discover structural motifs, a heatmap visualization to compare multiple experiments, hierarchical clustering of Glycan Binding Proteins with respect to their binding motifs and a structural search feature on the experimental data.

| | |
---|---
**Data in Database** | -
**Search Options** | -
**Availability** | <https://glycopattern.emory.edu>
**License** | -
**Status** | -
**Funding** | -
**Future Plans** | -
**Code Availablity** | -
**Contact** | <sanjay.agravat@emory.edu>

<br>

### 2-10. UniCarb-DB<a name="data210">
  UniCarb-DB is the glycomics fragmentation database that stores, integrates and processes data from manually annotated ms spectra.

| | |
---|---
**Data in Database** | MS/MS spectra, structures, peak lists, references, methods, tissue and taxonomy annotations
**Search Options** | Species, tissue, composition, recorded mass, observed mass, peak list
**Availability** | <http://www.unicarb-db.org>
**License** | CC
**Status** | Stable, maintained
**Funding** | NeCTAR, ANDS, STINT, SIB ExPASy
**Future Plans** | -
**Code Availablity** | Open Source
**Contact** | <niclas.karlsson@medkem.gu.se>
