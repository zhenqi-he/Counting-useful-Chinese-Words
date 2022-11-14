# Counting-useful-Chinese-Words
It is based on Baidu Lac model to count useful chinese words and characters in text documents

## Introduction
It is for analysising the useful chinese words or characters in text documents, which is usually applied in reply quality measurements.
Baidu Lac(https://github.com/baidu/lac) is used for word segmentation.
The useful chinese words here refer to nouns, adjectives, verbs and adverbs. The LAC model is firstly used to split text into words, and stop words from the stop words dictionary(Baidu stop words dictionary is used here) are excluded.

## Installation & Usage
Details of Installation of lac is in https://github.com/baidu/lac

Edit paths name in main.sh and simply run the command main.sh

Remainder: All texts are stored in the column named "text" in a csv file
