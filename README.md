### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.
### Output:
![wdm 9](https://github.com/user-attachments/assets/0a9f96f5-d6d6-4712-b7b5-970936972b79)
![wdm 9(1)](https://github.com/user-attachments/assets/0d00368f-6d16-4800-8c23-b670ba3d511c)
![wdm 9(2)](https://github.com/user-attachments/assets/a4671b51-578f-4ac5-b4aa-bd8e62f48b7a)
![wdm 9(3)](https://github.com/user-attachments/assets/15e8960b-163a-44b3-80a8-8cba938834e5)
### Result:
Thus implemententation of  preprocessing technique on Twitter Data using Rapidminer was done successfully.
