# Twitter Sentiment Analysis

## Description

Group project for an introduction to AI course taught between September 2023 and December 2023

Members
1. Daniel Nzambuli
2. Lydia Masabarakiza
3. Diana Nduku
4. Razia Omari

### Project Scope

- Create and test a model for sentiment analysis using
* vader - a basic tokenizer and sentiment analysis tool from `python NLTK`
* Roberta - a sentiment analysis pretrained tool offered by `hugging face`

- After trying to assess model accuracy using `old newspaper`  data from `kaggle` to see if the model can detect sentiments in  other languages

### Key Features
1. Exploritory Data Analysis
2. Sample Analysis using Vader Model
3. Using vader on Twitter Covid-19 data
4. Sample Analysis using Roberta Model
5. Using Roberta on Twitter Covid-19 data
6. Comparing Vader and Roberta

### Outline of AI Concepts Adopted in the Projects
1. Natural Language Processing to extract sentiments
2. Using pretrained models for tokenizing sentiments, pos-tagging, feature extracting and classiffying text into `positive` , `neutral` , or `negative`
3. Classification to group the tweets based on their positivity

### Strengths vader
* Short Text Compatibility: Well-adapted for the analysis of concise and informal texts, like those found on social media.
* Pre-existing Training: The model comes pre-trained on a substantial corpus, saving users time and resources.
* Rule-Based Methodology: Vader employs a rule-based approach for sentiment analysis.

### strength roberta
* Contextual Comprehension: Roberta excels in grasping context, a notable advancement beyond Vader's rule-centric method.
* Transfer Learning Prowess: It leverages transfer learning, displaying superior adaptability across tasks with minimal task-specific data.
* Exceptional Performance: Demonstrates top-tier performance in diverse natural language processing tasks.
* Nuanced Understanding: Surpasses Vader by capturing subtleties in sentiment expressions and intricate language structures.


### Limitations vader
* Misspellings and grammatical mistakes may cause the analysis to overlook important words or usage.
* Sarcasm and irony may be misinterpreted.
* Because VADER is built for English text, its performance might be affected when used to analyze sentiment in languages other than English..
* Discriminating jargon, nomenclature, memes, or turns of phrase may not be recognized.
VADER is based on a pre-built lexicon of words and sentiment scores. A word may not be accurately evaluated if it is not in the lexicon.

### Limitations roberta
* Training and using RoBERTa requires significant computational resources
* The accuracy of the model is reduced when handling domain-specific tasks or industries with specialized vocabulary.
* The RoBERTa model is trained on diverse datasets. The presence of bias in the training datasets will result in biased predictions. 
* Despite its ability to record long-term dependencies, RoBERTa has a token limit for input sequences. Long papers may be shortened, resulting in the loss of critical context.
