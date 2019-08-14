Monterey Bay Aquarium Research Institute (MBARI)
Francisco Chavez

In this folder are full biom files from MBARI projects. Be aware that these biom files are very large, 5MB to 1GB unzipped. Smaller examples with a limited number of OTUs but with a full set of sample metadata may be found in the folder asvBiomXchange/sample_data/MBARI/Example_biom_files

MBARI Biom files are created from a modified version of the banzai pipeline, see https://github.com/reikopm/mbonlive_banzai
This folder contains eDNA sample biom files for metabarcodes 12S, 16S, 18S, and COI. The biom format is from biom-format.org

The Biological Observation Matrix (BIOM) 

The BIOM file format represents biological samples by observation contingency tables. BIOM is a recognized standard for the 
Earth Microbiome Project and is a Genomics Standards Consortium supported project.

The BIOM format is designed for general use in broad areas of comparative -omics, such as marker-gene surveys, in which the 
primary use is to represent operational taxonomic unit (OTU) tables: the matrix contains counts corresponding to the number 
of times each OTU is observed in each sample.

<p aligh="center">
<img src="https://user-images.githubusercontent.com/1767453/60984701-04a12b00-a2f1-11e9-9cb1-e6378408acf9.png" width="500">
</p>
<p aligh="center">
<img src="https://user-images.githubusercontent.com/1767453/60984438-9492a500-a2f0-11e9-8efe-c4c74bbe8fae.png" width="500">
</p>

The BIOM file is an ascii text file with three sections, "data" (sequence reads), "rows" (observation metadata), 
and "cols" (sample metadata).
<p aligh="center">
<img src="https://user-images.githubusercontent.com/1767453/60297367-db3dd380-98dc-11e9-9934-f24c3105b5f2.PNG" width="500">
</p>

1. Sequence reads: OTU table from pipeline processing, usearch swarm clustering.
2. Observation metadata: MEGAN taxonomic assignments from NCBI blastn results. https://ab.inf.uni-tuebingen.de/software/megan6 
3. Sample metadata: Collection, laboratory, and processing metadata. Metadata are manually assembled; data are modeled following GSC MiMarks.

<p aligh="center">
<img src="https://user-images.githubusercontent.com/1767453/60214849-31e2d900-981b-11e9-9c07-fce268f877c3.PNG" width="500">
</p>

The sample metadata definitions are still a work in progress as such the metadata tracked from each biom may be different (2019 July).
See asvBiomXchange/sample_data/MBARI/standard_metadata_KW_RPM_CJC.pdf for current metadata information.

Metabarcodes from Monterey Bay California
1. 12S vertebrates
2. 16S microbes (bacteria & archaea)
3. 18S phytoplankton, invertebrates, and some vertebrates
4. COI invertebrates, some vertebrates and phytoplankton

For use in publication, authors should obtain written permission from MBARI's Director of Information and Technology 
Dissemination and Francisco Chavez. You should acknowledge MBARI as the data source in those publications and provide 
reprints to the MBARI library. 

MBARI provides these data "as is", with no warranty, express or implied, of the data quality or consistency. Data are 
provided without support and without obligation on the part of the Monterey Bay Aquarium Research Institute to assist in 
its use, correction, modification, or enhancement.
