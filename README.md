# Overview
This repository contains a set of Python scripts and experiments designed to perform various string matching tasks. The scripts provided cover a range of matching techniques, including exact string matching, intial+surname(abbraviation) matching, surname matching and fuzzy string matching,.

## Supported String Matching Strategies

### Exact String Matching: 
The script, [matchexactstring.py](matchexactstring/match_exact_string.py), deals with exact string matching. It provides a straightforward method to match strings precisely, without considering any variations or similarities.

### Initial+Surname Match: 
The script, [matchwithabbreviation.py](matchwithabbreviation/match_with_abbreviation.py), is dedicated to initial+surname matching. It implements a method to extract initials from a given name or a name with specific patterns. It intelligently handles various cases, ensuring accurate extraction and formatting of initials.

### Surname Match: 
The script, [matchsurname.py](matchsurname/match_surname.py), focuses on surname matching. It provides functionality to compare and match surnames, considering variations and common misspellings.

### Fuzzy String Match: 
[matchfuzzystring.py](matchfuzzystring/match_fuzzy_string.py) script is designed for fuzzy string matching. It employs algorithms that allow for matching strings that are similar but not necessarily identical, considering typos, variations, and other discrepancies.


### DeezyMatch:

The deezy mis trained and fine-tuned under a different repo. 

Please visit git repo: https://github.com/Shoilee/deezymatch_jrcnames


## Experiment

### On Ground Truth data: 
[exp300.ipynb](exp300/exp300.ipynb) script represents with ground truth data, which might involve specific configurations or variations of the matching algorithms. Please refer to the script for detailed information on the experiment.

### exp202.py: 
Similarly, [exp202.ipynb](exp202/exp202.ipynb)  represents Experiment with NMVW persons vs Bronbeek person name. This file likely contains specific settings, data, or methodologies related to the corresponding experiment. Refer to the script for detailed insights.

## Usage
To use the provided scripts, follow these general steps:

1. Clone the repository to your local machine:
```bash
git clone https://github.com/your-username/your-repository.git
```
2. Install and activate the environment
```bash
conda env create -f environment.yml
conda activate actor_linking
```
3. Navigate to the project directory:
```bash
cd exp-dictionary
```
1. Execute the desired script using Python:
```bash
ipython
%run your_script.ipynb
python exp*.ipynb
```

## Notes
- Ensure that you have Python installed on your machine before running the scripts.

- Check the specific script's documentation for any additional dependencies or requirements.

- Experiment scripts (exp300.py and exp202.py) may have specific instructions or data configurations. Refer to each script's comments or documentation for more details.

Feel free to explore and modify the scripts to suit your specific use cases. If you encounter any issues or have suggestions, please open an issue or submit a pull request.