# GloDB Website

GloDB is a curated reference database and associated bioinformatic pipeline for the environmental identification of arbuscular mycorrhizal fungi (AMF) using the large subunit (LSU) and long-read PacBio (SSU-ITS-LSU) regions.

[![Website](https://img.shields.io/badge/Website-glodb.org-blue)](https://www.glodb.org)
[![DOI](https://img.shields.io/badge/DOI-10.1111/nph.17080-blue)](https://doi.org/10.1111/nph.17080)

## Description

Arbuscular mycorrhizal fungi associate with ~80% of land plants worldwide, playing critical roles in plant growth, survival, and ecosystem function. GloDB provides an open, curated reference database and improved pipelines for environmental sequencing and identification of these fungi from environmental DNA samples.

The project includes:

- **GloDB** — LSU reference database with multiple curated versions (v10–v18)
- **LongGloDB** — Curated long-read PacBio database (SSU, ITS, LSU, and combined regions)
- **Pipelines** — Tools for placing study sequences into the GloDB backbone tree for operational taxonomic unit (OTU) or amplicon sequence variant (ASV) identification

## Site Navigation

| Page | Description |
|------|-------------|
| [Home](https://www.glodb.org) | Overview, database visualizations, and references |
| [Databases](https://www.glodb.org/databases.html) | Download GloDB and LongGloDB data files |
| [Pipelines](https://www.glodb.org/pipelines.html) | Pipeline tools for AMF identification |
| [About](https://www.glodb.org/about.html) | Project background and contact information |

## References

When using this resource, please cite the relevant publication(s):

- Delavaux, C. S. et al. (2021). Utility of large subunit for environmental sequencing of arbuscular mycorrhizal fungi: a new reference database and pipeline. *New Phytologist*, 229, 3048–3052. [![DOI](https://img.shields.io/badge/DOI-10.1111/nph.17080-blue)](https://doi.org/10.1111/nph.17080)
- Delavaux, C. S., Ramos, R. J., Sturmer, S. L. & Bever, J. D. (2022). Environmental identification of arbuscular mycorrhizal fungi using the LSU rDNA gene region: an expanded database and improved pipeline. *Mycorrhiza*, 32, 145–153. [![DOI](https://img.shields.io/badge/DOI-10.1007/s00572-022-01068-3-blue)](https://doi.org/10.1007/s00572-022-01068-3)
- Delavaux, C. S., Ramos, R. J., Stürmer, S. L. & Bever, J. D. (2024). An updated LSU database and pipeline for environmental DNA identification of arbuscular mycorrhizal fungi. *Mycorrhiza*, 1–5. [![DOI](https://img.shields.io/badge/DOI-10.1007/s00572-024-01159-3-blue)](https://doi.org/10.1007/s00572-024-01159-3)

## Building the Site

The site is built with [Quarto](https://quarto.org/). To render locally:

```bash
quarto render
```

To deploy:

```bash
quarto publish gh-pages
```

## Contact

- **Camille Delavaux** — c.delavaux@nioo.knaw.nl
- **Robert Ramos** — robert.ramos@stonybrook.edu

## License

Data and content are made available under open access for research and educational purposes.