# Tream Assemble Nextflow Pipeline

This Nextflow pipeline trims and assembles paired-end sequencing data.

## Usage

1. **Clone the repository and navigate to the project directory:**
 ```bash
 git clone https://github.com/Biswajit-Banerjee/NextFlow-demo
 ```

2. Set up the Conda environment:
```bash
conda env create -f environment.yml
conda activate ex3
```
3. Run the Nextflow pipeline:
```bash
nextflow run trim_assemble.nf --reads 'data/*_{R1,R2}.fastq.gz'
```
Replace `'data/*_{R1,R2}.fastq.gz'` with the path to your input fastq files.

## Output

The pipeline generates trimmed fastq files and assembly output in the designated directory.

## Requirements

- [Nextflow](https://www.nextflow.io/)
- [Conda](https://docs.conda.io/en/latest/)
- [FastQC](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/)
- [MultiQC](https://multiqc.info/)
- [Trimmomatic](http://www.usadellab.org/cms/?page=trimmomatic)
- [SPAdes](http://cab.spbu.ru/software/spades/)

## References

- [Nextflow Documentation](https://www.nextflow.io/docs/latest/index.html)
- [Conda Documentation](https://docs.conda.io/en/latest/)
- [FastQC Documentation](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/)
- [MultiQC Documentation](https://multiqc.info/)
- [Trimmomatic Documentation](http://www.usadellab.org/cms/?page=trimmomatic)
- [SPAdes Documentation](http://cab.spbu.ru/software/spades/)
