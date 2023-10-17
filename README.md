# Process of Elimination for Multiple Choice Reasoning

The official implementation of our paper *Process of Elimination for Multiple Choice Reasoning*.


## Prerequisites

Install dependencies:
```
pip install -r requirements.txt
```
Download data:
```
bash data/data_downloaders.sh
```
Download models:
```
bash models/model_downloaders/model_downloaders.sh
```

## Reproduce Results
Run scripts in `methods/` to reproduce results in the paper:
```
cd methods
bash 1_main_exp.sh
bash 2_logical_reasoning.sh
bash 3_mask.sh
bash 4_llm.sh
bash 5_few_shot.sh
bash 6_num_option.sh
```
The numbers in the script names indicate the order of the experiments in the paper.
The results will be saved in `results/`.
The LLM script is incomplete, and we will add the rest of the code soon.