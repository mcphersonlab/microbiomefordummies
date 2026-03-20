# Microbiome for Dummies

A beginner-friendly Quarto website covering microbiome bioinformatic tools, focusing on the [Biobakery](https://huttenhower.sph.harvard.edu/tools/) suite developed by the Huttenhower and Segata labs.

🌐 **Live site:** [https://mcphersonlab.github.io/microbiomefordummies/](https://mcphersonlab.github.io/microbiomefordummies/)

## Tools Covered

| Tool | Description |
|------|-------------|
| [HUMAnN](tools/humann.qmd) | Functional profiling of metagenomes |
| [MetaPhlAn](tools/metaphlan.qmd) | Taxonomic profiling from shotgun metagenomics |
| [PICRUSt2](tools/picrust2.qmd) | Predict metagenome function from 16S data |
| [PhyloPhlAn](tools/phylophlan.qmd) | High-resolution microbial phylogenetics |
| [StrainPhlAn](tools/strainphlan.qmd) | Strain-level metagenomic profiling |
| [ShortBRED](tools/shortbred.qmd) | Identify and quantify protein families |
| [WAAFLE](tools/waafle.qmd) | Detect horizontal gene transfer events |
| [MACARRoN](tools/macarron.qmd) | Metabolome prioritization |
| [metawibele](tools/metawibele.qmd) | Microbial protein function characterization |
| [baqlava](tools/baqlava.qmd) | Viral profiling from metagenomes |
| [MaAsLin2](tools/maaslin2.qmd) | Multivariable association discovery |
| [anpan](tools/anpan.qmd) | Pan-genome statistical models |
| [CCREPE](tools/ccrepe.qmd) | Compositional data correlation |

## Development

This site is built with [Quarto](https://quarto.org/) and deployed to GitHub Pages via GitHub Actions.

### Local rendering

```bash
# Install Quarto: https://quarto.org/docs/get-started/
quarto preview
```

### Deployment

The site is automatically rendered and deployed when changes are pushed to `main` via the GitHub Actions workflow in `.github/workflows/publish.yml`.
