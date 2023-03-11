Tibu.ai - Rule Based Telegram Chatbot

Microsoft/ Africa Leadership Academy / mDoc Health-Tech Hackathon.


## Background

Many patients in Kenya find it difficult to locate a qualified healthcare specialist around their area. This forces them to travel long distances to find one, possibly suggested to them by a friend, another physician or found online. This requires more time and usually costs more. Also, it is difficult to ascertain the credibility of the said physician.


### Solution:

Create a Chatbot that allows users to receive suggestions on recommended healthcare
facilities or providers based on their symptoms, diagnosis or test results. The suggestions will be generated from available datasets and a stored database of frequently asked questions (FAQs) from previous user interactions with the chatbot.

## Chatbot Functionality 
Implementation has been divided into 3 stages. The bot should be able to: 

### Stage 1:

1. Recommend a facility/provider based on symptoms.

2. Recommending a facility/provider based on specialty (as a redundancy)

### Stage 2

1. Recommending a facility/provider based on location.

### Stage 3

1. Recommending a facility/provider based on insurance type.

2. Recommending a facility/provider based on operation hours and days.

## Datasets
Included in this projects are the following datasets:

`specialist.xlsx`

 This dataset has over 13,000 health facilities and contains:
  1. Name of facility
  2. Level of care
  3. Facility type
  4. Ownership
  5. Opening days
  6. Opening times
  7. Geodata
  8. Number of beds
  9. Insurance providers accepted 


`symptoms.csv`

 This [Kaggle dataset](https://www.kaggle.com/datasets/itachi9604/disease-symptom-description-dataset) by Pranay Patil has columns containing diseases, their symptoms , precautions to be taken, and their weights.

`diag.spec.icd10.csv`

This is a modified [ICD-10](https://icd.who.int/browse10/2019/en#/) dataset where the healthcare experts in our group matched diagnoses with specialists.


## Roadmap

In future, the bot should transition from a rule based chatbot into one that utilizes Machine Learning.


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.


## Authors and Acknowledgement

Great thanks to each of the Group 13 Members for their work and effort in the project:

1. Monica Oyugi
2. Bruce Onduru
3. Hezron Munyakin
4. Fred Mutisya
5. Michael Obiero



## License

[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)
