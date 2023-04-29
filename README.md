This repository provides dataset and other materials for paper entitled: "Examining LLM's Awareness of the United Nations Sustainable Development Goals (SDGs)".

## Structure 
`dataset` folder include evaluation dataset in different formats that include both manual statements auto generated statements of true/false statements.


We select six topics related to UN SDGs. We consider two experimental setups---one with automatically generated text and another with manually crafted text. 

## Manual Input
For each chosen topic, five questions and five true and five false statements were manually curated. In curating the questions and corresponding statements, we ensured diversity in the sub-topics covered. 

## Auto-generated Statements
We utilize ChatGPT API (gpt-3.5-turbo model) to generate text for each topic where the ChatGPT agent plays the role of an expert advocate on each topic. We generate 20 questions and use each question as a prompt to generate 20 true and 20 false statements. Therefore, we generate 800 statements per topic, and overall, we generate 4,800 statements for evaluation on automated statements which we refer to as "Auto True/False Statements".



