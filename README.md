![RescueLine Logo Banner](https://user-images.githubusercontent.com/44092976/152698149-c7698fc6-4d91-4aa1-9277-f78ace5cda2e.jpg)
_RescueLine uses machine learning to classify emergency calls according to the nature of assistance required to dispatch the appropriate response team (fire,medic,search/rescue) and save lives._
[![Open in SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/rohitgarg025/aws-sagemaker-hackathon/blob/main/etl.ipynb>)

# AWS Disaster Response Hackathon

## Submitted by:
1. Rohit Garg
2. Aditya Mishra
3. Dhruv Nagpal
 
## Requirements
1. Python 3 or later
2. Jupyter Notebook Environment
3. Numpy, Pandas, Matplotlib, nltk, re 

## How to run
1. Clone the repo, and import it to a notebook environment. 
2. Run ```etl.ipynb```. This will extract, transfer, and load the datasets and create ```disaster.csv```. 
3. Run ```ml.ipynb```. This file will perform multilabel text classification on the input text once the model has been trained on ```disaster.csv``` created in step 2. 
4. Run all queries by calling ```predict_query(pipeline)``` function in ```ml.ipynb```!

## What is RescueLine?
Disasters cause hardship, and different individuals can require different kinds of help. A flood can trap someone inside a collapsed building, while someone else gets stuck on the roof, or someone suddenly has no access to drinking water or food, or needs emergency medical help. The flood of emergency calls can and often does overwhelm local response teams, which is why we have built RescueLine. RescueLine uses state of the art machine learning algorithms to automatically classify calls for help according to the nature of aid request, so that emergency responders can be dispatched quickly and with appropriate gear for the task. Running on AWS SageMaker, it is incredibly scalable and the cheapest such solution in the market, with essentially no server or infrastructure costs, and built in geo redundancy. RescueLine is how we will save lives.

