# VERSA-spine
A fully automized pipeline for information extraction from lumbar spine MRI radiology reports using GPT4

## Description

## Getting Started

### Dependencies
The scripts in this repository have been tested with Python 3.11.0.

### Installing
1. Set up a github API Key
2. Clone the repo
```
git clone git@github.com:michelle-tong18/VERSA-spine.git
```

## Running the algorithm
1. Create a file named `.env` with your information to access the OpenAI API
```
API_KEY=YOUR_KEY_HERE
API_VERSION=2023-09-01-preview
RESOURCE_ENDPOINT=https://YOUR_URL_HERE
```
2. `VERSA-spine_pipeline.ipynb` for information extraction:
    1. Prepare a `YOUR_FILENAME_HERE.csv` with radiology reports in a column named *note_text*
    2. Update the `file_name` and `save_path` variables
    3. Run the notebook
3. `VERSA-spine_embedding_analysis.ipynb` for embedding assessment: 
    1. Update the `save_path` variable
    2. Run the notebook

## Acknowledgements
* This work was supported by the [].
  
## License
Distributed under the MIT License. See LICENSE.txt for more information.

## Citation
* Ziegeler K, Kreutzinger V, Tong MW, Chin CT, Bahroos E, Wu P-H, Bonnheim N, Fields AJ, Lotz JC, Link TM, et al. Information Extraction from Lumbar Spine MRI Radiology Reports Using GPT4: Accuracy and Benchmarking Against Research-Grade Comprehensive Scoring. Diagnostics. 2025; 15(7):930. [10.1016/j.mri.2024.110222](https://doi.org/10.3390/diagnostics15070930)
