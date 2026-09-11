# gwas-gene-annotation
Connecting simulated GWAS signals to candidate genes using genomic intervals

# GWAS Gene Annotation

This project demonstrates how GWAS variants can be connected to candidate genes using genomic intervals.

## Objectives

- Create simulated GWAS results
- Create simulated gene annotations
- Match variants to overlapping gene regions
- Rank annotated variants by p-value
- Visualise association signals by gene

## Tools

- Python
- pandas
- NumPy
- Matplotlib
- Google Colab

## Key Findings

The strongest annotated signal was rs2009, which overlapped the simulated gene GENE_E and had a p-value of 1 × 10^-9.

The second strongest signal was rs2003, which overlapped GENE_B and had a p-value of 2 × 10^-8.

Both variants passed the conventional genome-wide significance threshold of 5 × 10^-8.

## Limitations

The data and gene annotations are simulated. The assignments are based only on whether a variant falls within a simulated gene interval.

Real gene annotation would require reference genome coordinates and tools such as Ensembl VEP, ANNOVAR, or a similar annotation resource.

## Files

- `gwas-gene-annotation.ipynb` — analysis notebook
