# DS210-Project-Proposal
Dataset Description:

This dataset was downloaded from the EMBL-EBI Antimicrobial Resistance Portal. It contains information about antibiotic resistance phenotypes, resistance-associated genes, and bacterial sample characteristics.

Research Question: What factors are associated with ampicillin resistance in Escherichia coli isolates?

Data Source:  https://www.ebi.ac.uk/amr/

Original Dataset: 1,191 rows and 51 variables.

Cleaned Dataset: 1,174 rows and 12 variables.

The original data contain combined antimicrobial resistance phenotype and genotype records. Each row represents a resistance record linked to a bacterial sample and genetic annotation.

Variable	Type:
resistance (Categorical): Ampicillin resistance phenotype: resistant or susceptible.

antibiotic (Categorical): Name of the antibiotic tested.

species (Categorical): Name of the bacterial species.

gene (Categorical): Name of the identified resistance-associated gene.

BioSample_ID	Identifier	Unique ID of the bacterial sample.

assembly_ID	Identifier	GenBank ID of the sample's genome assembly.

genus	Categorical	Genus of the bacterium.

species	Categorical	Species of the bacterium.

organism	Categorical	Full name of the organism.

taxon_id	Identifier	NCBI taxonomy ID of the organism.

isolate	Identifier	Name the submitter gave the isolate.

host	Categorical	Host the sample came from, such as Homo sapiens or "other (non-clinical isolate)".

SRA_accession	Identifier	ID of the sequencing data in the Sequence Read Archive.

laboratory_typing_method	Categorical	Lab method used to test susceptibility: broth dilution, agar dilution, or disk diffusion.

platform	Categorical	Automated testing instrument, when reported.

ast_standard	Categorical	Standard used to decide resistant or susceptible: CLSI, EUCAST, or EU.

gen_antibiotic_ontology	Text	Antibiotic Resistance Ontology term and link for the drug.

region	Text	Sequence in the genome where the resistance element was found.

region_start	Quantitative	Start position of the element on that sequence, in base pairs.

region_end	Quantitative	End position of the element on that sequence, in base pairs.

strand	Categorical	DNA strand the element is on (+ or -).

id	Identifier	ID of the assembly feature where the element was found.

gene_symbol	Categorical	Gene that carries the resistance-associated mutation.

amr_element_symbol	Categorical	Exact mutation found in the gene.

element_type	Categorical	Type of element detected. All records are AMR.

element_subtype	Categorical	Subtype of element. All records are POINT.

class	Categorical	Drug class the element affects. All records are MULTIDRUG.

subclass	Text	Drugs the element is linked to.

split_subclass	Categorical	The drug this record matches. All records are AMPICILLIN.

amrfinderplus_method	Categorical	Detection method code from AMRFinderPlus. All records are POINTP.

reference_accession	Identifier	ID of the reference protein the gene was compared with.

reference_name	Text	Name of that reference protein.

reference_sequence_coverage	Quantitative	How much of the reference sequence the hit covers, in percent (%).

reference_sequence_identity	Quantitative	How closely the gene matches the reference sequence, in percent (%).

gen_evidence_accession	Text	Supporting evidence ID. It is empty in this dataset.

HMM_evidence_description	Text	Supporting evidence description. It is empty in this dataset.

gen_annotation_link	Text	Link to the annotation files for the genome.

annotation_tool_version	Categorical	Version of AMRFinderPlus used.

annotation_tool_mode	Categorical	Mode the annotation tool ran in (Fast or Full).

collection_year	Quantitative	Year the sample was collected, in calendar years.

host_age	Quantitative	Age of the human host, in years. About 93% is missing.

host_sex	Categorical	Sex of the human host. About 93% is missing.

isolation_source	Text	Where the sample was taken from, as the submitter wrote it.

isolation_source_category	Categorical	Standardized body-site category for the source.

isolation_latitude	Quantitative	Latitude of collection, in decimal degrees. 

isolation_longitude	Quantitative	Longitude of collection, in decimal degrees. 

AMR_associated_publications	Identifier	PubMed ID of a related publication.

used_ECOFF	Categorical	Whether an epidemiological cutoff was used to call the result. 

database	Categorical	Database the record came from.

country	Categorical	Country where the sample was collected.

geographical_region	Categorical	Continent-level region where the sample was collected.

geographical_subregion	Categorical	Smaller region within the continent, such as South-eastern Asia.
 
