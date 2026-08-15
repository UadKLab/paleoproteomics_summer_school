 ### _De novo_ section for PAASTA Bioinformatics Summer School 2026

This hands-on notebook takes participants from a PRIDE `.raw` file through `mzML` conversion, InstaNovo *de novo* prediction, spectrum annotation, and confidence assessment. An optional final section covers confidence calibration, FDR control, and PSM QC with winnow.

**Quick Start**: [Open `paleoproteomics_instanovo.ipynb` in Google Colab](https://colab.research.google.com/github/UadKLab/paleoproteomics_summer_school/blob/main/paleoproteomics_instanovo.ipynb)<br/>

**Credits**: This notebook was created by Yun Chiang and Jeroen van Goey.
<br/>
**used in this practical**:
> [ThermoRawFileParser](https://github.com/compomics/ThermoRawFileParser) To convert Thermo `.raw` to .mzML<br/>
> [InstaNovo](https://github.com/instadeepai/InstaNovo) For _de novo_ sequencing <br/> 
> [InstaNovo Hugging Face](https://huggingface.co/spaces/InstaDeepAI/InstaNovo) For quick _de novo_ sequencing online <br/>
> [spectrum_utils](https://github.com/bittremieuxlab/spectrum_utils) For spectra visualisation <br/>
> [winnow](https://github.com/instadeepai/winnow) For confidence calibration and FDR control <br/>
