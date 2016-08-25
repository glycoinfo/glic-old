---
title: Database Resources
layout: default
---
<h2>1. Glossary for Database Resources</h2>
<h3>1-1. Data</h3>
<ul><li><strong>Structure</strong><br>
Structure of a molecule represented in one or several sequence formats or graphicalrepresentation.</li><br>
<li><strong>Database reference</strong><br>
References to other databases of the same type containing the same molecule.</li><br>
<li><strong>Species annotation</strong><br>
Biological annotation describing the species the structure is found.</li><br></ul>
<h3>1-2. Search options</h3>
<ul><li><strong>Structure search</strong><br>
Allows searching for a structure by specifying is sequence.</li><br>
<li><strong>Sub-structure search</strong><br>
Search for structure based on a query structure that is a substructure of the structures in the search result.</li><br>
<li><strong>Maximum common substructure search (MCS)</strong><br>
Search of structures based on shared substructures with the query structure. The less query structure and another structure have in common the lower the score. If query structure and queried structure are identical or the query structure is subsumed by the other structure the score is maximum.</li><br>
<li><strong>Similarity search</strong><br> 
Search structures that are similar to a query structure. This search is different to the sub-structure search or the MCS search those residues and linkages may vary between the query and result structure.</li><br>
<li><strong>Search by species</strong><br>  
Search of structures based on their species annotation. This may allow for searches by higher species organization, such as Genus, Rank or Kingdoms.</li><br></ul>
<h2>2. Database Resources</h2>
<h3>2-1. GlycomeDB</h3>
<p>Meta database that integrates the structures from several glycomics databases (CFG, KEGG, GLYCOSCIENCES.de, GlycoBase, JCGGDB, BCSDB, PDB, GlycO and Carbbank) into one consistent sequence representation and creating a unique index of all structures present in the integrated database. Species annotations from the other databases are retrieved as well and integrated using the NCBI Taxonomy. Each structure in GlycomeDB is linked back to the original database allowing finding and browsing all occurrences of a structure in multiple databases.</p>
<table>
<tr>
<td class="title"><strong>Data in database</strong></td>
<td class="content">structure, databases references, species annotation</td>
</tr>
<tr>
<td class="title"><strong>Search options</strong></td>
<td class="content">structure search, sub-structure search, similarity search, maximum common substructure search, species search</td>
</tr>
<tr>
<td class="title"><strong>Availability</strong></td>
<td class="content"><a href="http://www.glycome-db.org/">http://www.glycome-db.org/</a></td>
</tr>
<tr>
<td class="title"><strong>License</strong></td>
<td class="content">None</td>
</tr>
<tr>
<td class="title"><strong>Status</strong></td>
<td class="content">stable, maintained</td>
</tr>
<tr>
<td class="title"><strong>Funding</strong></td>
<td class="content">-</td>
</tr>
<tr>
<td class="title"><strong>Future plans</strong></td>
<td class="content">-</td>
</tr>
<tr>
<td class="title"><strong>Code availability</strong></td>
<td>on request</td>
</tr>
<tr>
<td class="title"><strong>Contact</strong></td>
<td class="content">Rene Ranzinger:&nbsp;<a href="mailto:rene@ccrc.uga.edu">rene@ccrc.uga.edu</a></td></tr>
</table>

<h3>2-2. UniCarbKB</h3>
<p>The UniCarb KnowledgeBase (UniCarbKB) offers public access to a growing, curated database of information on the glycan structures of glycoproteins. UniCarbKB is an international effort that aims to further our understanding of structures, pathways and networks involved in glycosylation and glyco-mediated processes by integrating structural, experimental and functional glycoscience information. This initiative builds upon the success of the glycan structure database GlycoSuiteDB, together with the informatic standards introduced by EUROCarbDB, to provide a high-quality and updated resource to support glycomics and glycoproteomics research. UniCarbKB provides comprehensive information concerning glycan structures, and published glycoprotein information including global and site-specific attachment information.</p>
<table>
<tr>
<td class="title"><strong>Data in database</strong></td>
<td class="content">structure, glycoproteins, site-specific information, databases references, species annotation, tissue, cell line, biological fluid, methods</td>
</tr>
<tr>
<td class="title"><strong>Search options</strong></td>
<td class="content">structure search, sub-structure search, species search, glycoprotein search, UniProtKB accession number search, tissue search, composition search </td>
</tr>
<tr>
<td class="title"><strong>Availability</strong></td>
<td class="content"><a href="http://unicarbkb.org">http://unicarbkb.org</a></td>
</tr>
<tr>
<td class="title"><strong>License</strong></td>
<td class="content">CC</td>
</tr>
<tr>
<td class="title"><strong>Status</strong></td>    
<td class="content">stable, maintained</td>
</tr>
<tr>
<td class="title"><strong>Funding</strong></td>
<td class="content">The National eResearch Collaboration Tools and Resources (NeCTAR) Project; Swiss National Science Foundation</td>
</tr>
<tr>
<td class="title"><strong>Future plans</strong></td>    
<td class="content">Continued curation, better integration and support for GlycoRDF, improved search and query functionality</td>
</tr>    
<tr>
<td class="title"><strong>Code availability</strong></td>
<td class="content">Release 1 GitHub public, On-going developments BitBucket user managed</td>
</tr>
<tr>
<td class="title"><strong>Contact</strong></td>
<td class="content"></td>
</tr>
</table>

<h3>2-3. Carbohydrate Structure Database (CSDB)</h3>
<p>The Carbohydrate Structure Databases (CSDBs) store structural, bibliographic, taxonomic, NMR spectroscopic, and other data on natural carbohydrates and their derivatives published in the scientific literature. The CSDB project was launched in 2005 for bacterial saccharides (as BCSDB). Currently, it includes two parts, the Bacterial CSDB and the Plant&Fungal CSDB. In March 2015, these databases were merged to the single Carbohydrate Structure Database (CSDB). The combined CSDB includes information on bacterial and archaeal glycans and derivatives (the coverage is close to complete), as well as on plant and fungal glycans and glycoconjugates (almost all structures published up to 1998). CSDB is regularly updated via manual expert annotation of original publications. Both newly annotated data and data imported from other databases are manually curated. The CSDB data are exportable in a number of modern formats, such as GlycoRDF. CSDB provides additional services for simulation of 1H, 13C and 2D NMR spectra of saccharides, NMR-based structure prediction, glycan-based taxon clustering, and other.</p>
<table>
<tr>
<td class="title"><strong>Data in database</strong></td>
<td class="content">structures, NMR spectra, taxon annotations, bibliographic annatations, databases references, supplementary data</td>
</tr>
<tr>
<td class="title"><strong>Search options</strong></td>
<td class="content">structure search, sub-structure search, composition search, taxon search, bibliography search, NMR signal search, id search</td>
</tr>
<tr>
<td class="title"><strong>Availability</strong></td>
<td class="content"><a href="http://csdb.glycoscience.ru/">http://csdb.glycoscience.ru/</a></td>
</tr>
<tr>
<td class="title"><strong>License</strong></td>
<td class="content">None (free)</td>
</tr>
<tr>
<td class="title"><strong>Status</strong></td>
<td class="content">stable, maintained</td>
</tr>
<tr>
<td class="title"><strong>Funding</strong></td>
<td class="content">Russian Foundation for Basic Research</td>
</tr>
<tr> 
<td class="title"><strong>Future plans</strong></td>
<td class="content">see papers</td>
</tr>
<tr>
<td class="title"><strong>Code availability</strong></td>
<td class="content">no</td>
</tr>
<tr>
<td class="title"><strong>Contact</strong></td>
<td class="content">Phyl Toukach:&nbsp;<a href="mailto:netbox@toukach.ru">netbox@toukach.ru</a></td></strong></td>
</tr>
</table>

<h3>2-4. SugarBindDB</h3>
<p>The SugarBind Database (SugarBindDB) covers knowledge of glycan binding of human pathogen lectins and adhesins. It is a curated database; each glycan-binding event is associated with at least one published reference. The core data of SugarBindDB is a triple constituted of a pathogenic agent, a lectin/adhesin and a glycan ligand. SugarBindDB content is displayed in views. All views are interconnected.</p>
<table>
<tr>
<td class="title"><strong>Data in database</strong></td>
<td class="content">structure, pathogenic lectin/adhesin, protein-carbohydrate interactions, cross-references, binding annotation, tissue, disease, symptoms, methods</td>
</tr>
<tr>
<td class="title"><strong>Search options</strong></td>
<td class="content">species search, lectin search, ligand search, tissue search, disease search, multi-criteria search</td> 
</tr>
<tr>
<td class="title"><strong>Availability</strong></td>
<td class="content"><a href="http://sugarbind.expasy.org">http://sugarbind.expasy.org</a></td>
</tr>
<tr>
<td class="title"><strong>License</strong></td>
<td class="content">CC</td>
</tr>
<tr>
<td class="title"><strong>Status</strong></td>
<td class="content">stable, maintained</td>
</tr>
<tr>
<td class="title"><strong>Funding</strong></td>
<td class="content">SIB Swiss Institute of Bioinformatics + Swiss National Fund</td>
</tr>
<tr>
<td class="title"><strong>Future plans</strong></td>
<td class="content">increased data integration, continued data curation, addition of binding prediction tools</td>
</tr>
<tr>
<td class="title"><strong>Code availability</strong></td>
<td class="content"><a href="https://bitbucket.org/sib-pig/sugarbind">https://bitbucket.org/sib-pig/sugarbind</a></td>
</tr>
<tr>
<td class="title"><strong>Contact</strong></td>
<td class="content">-</td>
</tr>
</table>

<h3>2-5. Glycosciences.DB</h3>
<p>Database of the Glycosciences.de portal. Contains CarbBank structures + PDB carbohydrates + structures with NMR shifts extracted from the literature.</p>
<table>
<tr>
<td class="title"><strong>Data in database</strong></td>
<td class="content">structure, 3D structure models, pdb data, nmr shifts, species annotation, literature references</td>
</tr>
<tr>
<td class="title"><strong>Search options</strong></td>
<td class="content">structure search, sub-structure search, motif search, n-glycan properties search, literature search, nmr peak search</td>
</tr>
<tr>
<td class="title"><strong>Availability</strong></td>
<td><a href="http://www.glycosciences.de/database/">http://www.glycosciences.de/database/</a></td>
</tr>
<tr>
<td class="title"><strong>License</strong></td>
<td class="content">None</td>
</tr>
<tr>
<td class="title"><strong>Status</strong></td>
<td class="content">stable, maintained</td>
</tr>
<tr>
<td class="title"><strong>Funding</strong></td>
<td class="content">-</td>
</tr>
<tr>
<td class="title"><strong>Future plans</strong></td>
<td class="content">-</td>
</tr>
<tr>
<td class="title"><strong>Code availability</strong></td>
<td class="content"></td>
</tr>
<tr>
<td class="title"><strong>Contact</strong></td>
<td class="content">Thomas Lütteke:&nbsp;<a href="mailto:thomas.luetteke@vetmed.uni-giessen.de">thomas.luetteke@vetmed.uni-giessen.de</td>
</tr>
</table>

<h3>2-6. MonosaccharideDB</h3>
<p>Monosaccharide database. Contains monosaccharides + name parsing / encoding routines.</p>
<table>
<tr>
<td class="title"><strong>Data in database</strong></td>
<td class="content">monosaccharide properties, residue names</td>
</tr>
<tr>
<td class="title"><strong>Search options</strong></td>
<td class="content">name search, properties search</td>
</tr>
<tr>
<td class="title"><strong>Availability</strong></td>
<td class="content"><a href="http://www.mononsaccharidedb.org">http://www.mononsaccharidedb.org</a></td>
</tr>
<tr>
<td class="title"><strong>License</strong></td>
<td class="content">-</td>
</tr>
<tr>
<td class="title"><strong>Status</strong></td>
<td class="content">stable, maintained</td>
</tr>
<tr>
<td class="title"><strong>Funding</strong></td>
<td class="content">-</td>
</tr>
<tr>
<td class="title"><strong>Future plans</strong></td>
<td class="content">-</td>
</tr>
<tr>
<td class="title"><strong>Code availability</strong></td>
<td class="content"></td>
</tr>
<tr>
<td class="title"><strong>Contact</strong></td>
<td class="content">Thomas Lütteke:&nbsp;<a href="mailto:thomas.luetteke@vetmed.uni-giessen.de">thomas.luetteke@vetmed.uni-giessen.de</td>
</tr>
</table>

<h3>2-7. GlycoMapsDB</h3>
<p>Database of conformational maps of glycosidic linkages</p>
<table>
<tr>
<td class="title"><strong>Data in database</strong></td>
<td class="content">conformational maps derived from MD simulations</td>
</tr>
<tr>
<td class="title"><strong>Search options</strong></td>
<td class="content">disaccharide search</td>
</tr>
<tr>
<td class="title"><strong>Availability</strong></td>
<td class="content"><a href="http://www.glycosciences.de/modeling/glycomapsdb/">http://www.glycosciences.de/modeling/glycomapsdb/</a></td>
</tr>
<tr>
<td class="title"><strong>License</strong></td>
<td class="content">-</td>
</tr>
<tr>
<td class="title"><strong>Status</strong></td>
<td class="content">stable</td>
</tr>
<tr>
<td class="title"><strong>Funding</strong></td>
<td class="content">-</td>
</tr>
<tr>
<td class="title"><strong>Future plans</strong></td>
<td class="content">-</td>
</tr>
<tr>
<td class="title"><strong>Code availability</strong></td>
<td class="content"></td>
</tr>
<tr>
<td class="title"><strong>Contact</strong></td>
<td class="content">Thomas Lütteke:&nbsp;<a href="mailto:thomas.luetteke@vetmed.uni-giessen.de">thomas.luetteke@vetmed.uni-giessen.de</td>
</tr>
</table>

<h3>2-8. GlyTouCan</h3>
<p>Glycan structure/sequence/composition repository</p>
<table>
<tr>
<td class="title"><strong>Data in database</strong></td>
<td class="content">Glycan structures, as images, GlycoCT and WURCS, and their motifs, monosaccharides and linked to other related databases including GlycomeDB, BCSDB, GlycoEpitope, with others continuing to be added.  Each glycan structure is assigned a GlyTouCan ID.</td>
</tr>
<tr>
<td class="title"><strong>Search options</strong></td>
<td class="content">Graphical and textual substructure search, ID search and motif search</td>
</tr>
<tr>
<td class="title"><strong>Availability</strong></td>
<td class="content"><a href="http://www.glytoucan.org">http://www.glytoucan.org</a></td>
</tr>
<tr>
<td class="title"><strong>License</strong></td>
<td class="content">CC-BY</td>
</tr>
<tr>
<td class="title"><strong>Status</strong></td>
<td class="content">stable, maintained</td>
</tr>
<tr>
<td class="title"><strong>Funding</strong></td>
<td class="content">Integrated Database Project of Japan</td>
</tr>
<tr>
<td class="title"><strong>Future plans</strong></td>
<td class="content">Incorporation of UniCarbKB and other JCGGDB databases</td>
</tr>
<tr>
<td class="title"><strong>Code availability</strong></td>
<td class="content">open source</td>
</tr>
<tr>
<td class="title"><strong>Contact</strong></td>
<td class="content">Kiyoko F. Aoki-Kinoshita:&nbsp;<a href="kkiyoko@soka.ac.jp">kkiyoko@soka.ac.jp</a></td>
</tr>
</table>

<h3>2-9. GlycoPattern</h3>
<p>GlycoPattern is Web-based bioinformatics resource to
support the analysis of glycan array data for the Consortium for Functional Glycomics. This resource includes algorithms and tools to discover structural motifs, a heatmap visualization to compare multiple experiments, hierarchical clustering of Glycan Binding Proteins with respect to their binding motifs and a structural search feature on the experimental data.</p>
<table>
<tr>
<td class="title"><strong>Data in database</strong></td>
<td class="content"></td>
</tr>
<tr>
<td class="title"><strong>Search options</strong></td>
<td class="content"></td>
</tr>
<tr>
<td class="title"><strong>Availability</strong></td>
<td class="content"><a href="https://glycopattern.emory.edu/">https://glycopattern.emory.edu/</a></td>
</tr>
<tr>
<td class="title"><strong>License</strong></td>
<td class="content"></td>
</tr>
<tr>
<td><strong>Status</strong></td>
<td class="content"></td>
</tr>
<tr>
<td class="title"><strong>Funding</strong></td>
<td></td>
</tr>
<tr>
<td class="title"><strong>Future plans</strong></td>
<td class="content"></td>
</tr>
<tr>
<td class="title"><strong>Code availability</strong></td>
<td class="content"></td>
</tr>
<tr>
<td class="title"><strong>Contact</strong></td>
<td class="content"><a href="sanjay.agravat@emory.edu">sanjay.agravat@emory.edu</a></td>
</tr>
</table>

<h3>2-10. UniCarb-DB</h3>
<p>UniCarb­DB is the glycomics fragmentation database that stores, integrates and processes data from manually annotated ms spectra. </p>
<table>
<tr>
<td class="title"><strong>Data in database</strong></td>
<td class="content">MS/MS spectra, structures, peak lists, references, methods, tissue and taxonomy annotations</td>
</tr>
<tr>
<td class="title"><strong>Search options</strong></td>
<td class="content">Species, tissue, composition, recorded mass, observed mass, peak list</td>
</tr>
<tr>
<td class="title"><strong>Availability</strong></td>
<td class="content"><a href="http://www.unicarb-db.org/">http://www.unicarb-db.org/</a></td>
</tr>
<tr>
<td class="title"><strong>License</strong></td>
<td class="content">CC</td>
</tr>
<tr>
<td><strong>Status</strong></td>
<td class="content">Stable, maintained</td>
</tr>
<tr>
<td class="title"><strong>Funding</strong></td>
<td>NeCTAR, ANDS, STINT, SIB ExPASy</td>
</tr>
<tr>
<td class="title"><strong>Future plans</strong></td>
<td class="content"></td>
</tr>
<tr>
<td class="title"><strong>Code availability</strong></td>
<td class="content">Open Source</td>
</tr>
<tr>
<td class="title"><strong>Contact</strong></td>
<td class="content"><a href="niclas.karlsson@medkem.gu.se">niclas.karlsson@medkem.gu.se</a></td>
</tr>
</table>
