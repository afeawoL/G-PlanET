# G-PlanET

# RoboSense-methods


## Installation 

# Run the folllowing to set up your environment.:
```
conda create -n robosense python=3.8.19
conda activate robosense 

pip install -r requirements.txt
```

## Repository FileStructure

`data`: Contains the INK-USC/G-PlanET dataset, and scripts to convert the dataset for huggingface,tapex and iterative training .

`script`: Includes all the script needed in the main experiment. 

`evaluation`: The proceses needed to run test on the models framework and its code

`main`: Includes all the code used in the main experiment.


## Scripts

- `data_init.sh`: - Runs initiaiizing dataset procesing steps.
- `bart_train.sh`: Trains the mmodel.
- `bart_test.sh`: Evaluates model training, validating the model against test data.
- `bart_iter_test.sh`: Runs a test on the model with iterative self-training.
- `bart_table_iter_test.sh`: Ealuates model trainig, validating the model against iterative training table.
- `tapex_train.sh`: Trains and evaluates tapex model
- `tapex_test.sh`: Tests tapex model, validating against test data.

# NOTE: Check and fill in your data path and model path in the scripts before execution

Models used: `facebook/bart-base` and `facebook/bart-large`. All models can be found on the HuggingFace Hub.

