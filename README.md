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


Use
```
bash script/data_init.sh

```

NOTE: Check and fill in your data path and model path in the scripts before execution

Models used: `facebook/bart-base` and `facebook/bart-large`. All models can be found on Huggingface

