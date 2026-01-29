# Raw2AIRR
### #This tool is initially created for MSc dissertation project "BCR_classification_model"
Raw2AIRR is a bioinformatic pipeline that is used to process raw illumina reads 
of B-cell receptor (BCR). The tool will will start from undergoing paired-end 
assemble, quality-control, and collapse of duplicated reads. Then, the reads 
undergo alignment and annotation with OGRDB database to transform the reads into machine readable standardised file that represents the adaptive immune receptor repertoire data.

Note: Please configure according to the sequencing method
1. PRIMERS used for the sequencing should be configured using "presto/Primers.fasta"
2. Sample name should be configured using "/snakeconfig.yaml"
