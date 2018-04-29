# Dynamic-memory-networks-plus-Pytorch

[DMN+](https://arxiv.org/abs/1603.01417) implementation in Pytorch for question answering on the bAbI 10k dataset.

## Contents
| file | description |
| --- | --- |
| `babi_loader.py` | declaration of bAbI Pytorch Dataset class |
| `dmn_plus.py` | contains DMN+ model and training code |
| `Code_step_by_step.ipynb` | explains each module with good demostration for each module |
| `Project_DemoFinal.ipynb` | Demo using pretainedmodels, shows how attention is getting shifted |
| `get_data.sh` | shell script to fetch bAbI tasks  |

## Downloading Data
Run the included shell script to fetch the data  

    chmod +x get_data.sh
    ./fetch_data.sh

## Understaning code
Code_step_by_step.ipynb is specially made to understand code step by step.

## Training Model
Run dmn_plus.py to train model 

    python dmn_plus.py
 

## Using Pretrained model
Run Project_DemoFinal.ipynb to use pretrained model


| Task ID | This Repo | Xiong et al |
| :---: | :---: | :---: |
| 1 | 100% | 100% |
| 2 | 96.8% | 99.7% |
| 3 | 89.2% | 98.9% |
| 4 | 100% | 100% |
| 5 | 99.5% | 99.5% |
| 6 | 100% | 100% |
| 7 | 97.8% | 97.6% |
| 8 | 100% | 100% |
| 9 | 100% | 100% |
| 10 | 100% | 100% |
| 11 | 100% | 100% |
| 12 | 100% | 100% |
| 13 | 100% | 100% |
| 14 | 99% | 99.8% |
| 15 | 100% | 100% |
| 16 | 51.6% | 54.7% |
| 17 | 86.4% | 95.8% |
| 18 | 97.9% | 97.9% |
| 19 | 99.7% | 100% |
| 20 | 100% | 100% |
