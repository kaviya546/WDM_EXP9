### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 25/08/24
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
![WhatsApp Image 2024-08-25 at 19 52 56_6d3dcf02](https://github.com/user-attachments/assets/0da3aefb-465d-4a47-bcba-5aa5867729ec)
![WhatsApp Image 2024-08-25 at 19 53 11_545bd43b](https://github.com/user-attachments/assets/23f81db3-bae8-4784-bdf0-0b7d306a20bf)
![WhatsApp Image 2024-08-25 at 19 53 30_472df6c9](https://github.com/user-attachments/assets/0322e421-c6d9-417f-aad3-c9423f4a809b)
![WhatsApp Image 2024-08-25 at 19 54 31_e68bdea2](https://github.com/user-attachments/assets/dbafd08b-6e5a-401d-8c58-2b64431ece4e)


### Result:
implemented preprocessing technique on Twitter Data using Rapidminer successfully
