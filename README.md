# MAG Binning Workflow

Nextflow workflow to facilitate comparison of metagenome-assembled genome binning
across metagenomes and binning parameter settings

## Invocation

Install nextflow (requires Java 8 or later and conda on system):

    curl -s https://get.nextflow.io | bash


Edit `nextflow.config` and `run_params.csv` to select input and metagenome assembly/binning run parameters respectively. 

Then Execute workflow (in this example on test data with 15 CPUs), only input is folder containing fasta files

    ./nextflow run main.nf 
    
