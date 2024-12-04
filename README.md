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
* Ziegeler K, Kreutzinger V, Tong MW, Chin CT, Bahroos E, Bonnheim N, Fields AJ, Lotz J, Link TM, Majumdar S. A fully automized pipeline for information extraction from lumbar spine MRI radiology reports using GPT4: opportunities and challenges in low-back pain.
