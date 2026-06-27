# Mental Health Support Chatbot

## Project Overview

This project is part of the DevelopersHub AI/ML Engineering Internship.

The goal of this task is to build a basic mental health support chatbot that gives supportive and empathetic responses for stress, anxiety, sadness, and emotional wellness.

The chatbot is fine-tuned using a small language model and the EmpatheticDialogues dataset.

## Objective

Build a chatbot that can provide gentle and empathetic responses to emotional wellness-related messages.

## Dataset

Dataset used:

```text
EmpatheticDialogues
````

The dataset contains human conversations with emotional and empathetic responses.

## Model Used

```text
DistilGPT2
```

DistilGPT2 was used because it is smaller and easier to fine-tune compared to larger language models.

## Libraries Used

```text
torch
pandas
datasets
transformers
accelerate
```

## Tools and Frameworks

```text
Python
Jupyter Notebook
Hugging Face Transformers
Hugging Face Datasets
Hugging Face Trainer API
```

## Project Steps

1. Installed required libraries
2. Imported necessary packages
3. Checked whether GPU was available
4. Loaded the EmpatheticDialogues dataset
5. Inspected the dataset
6. Converted the dataset into a pandas DataFrame
7. Selected a smaller training subset
8. Formatted the data into User and Bot conversation style
9. Loaded DistilGPT2 tokenizer and model
10. Added padding token
11. Tokenized the dataset
12. Created a data collator
13. Set training arguments
14. Created a Trainer object
15. Fine-tuned the model
16. Saved the fine-tuned model
17. Loaded the saved model
18. Added a crisis safety filter
19. Created a chatbot response function
20. Tested chatbot responses
21. Saved test results to a CSV file

## Safety Filter

A crisis safety filter was added to detect serious messages related to self-harm or suicide.

If a crisis-related message is detected, the chatbot does not generate a normal response. Instead, it encourages the user to contact emergency services, a trusted person, or a crisis helpline.

## Example Inputs

```text
I feel very stressed about my exams.
I feel anxious today.
I am lonely and sad.
I am worried about my future.
I want to hurt myself.
```

## Evaluation

The chatbot was tested using different emotional wellness messages.

The responses were checked for:

```text
Empathy
Supportive tone
Safety handling
Relevance
Clarity
```

## Results

The chatbot was able to generate supportive responses for stress, anxiety, sadness, and loneliness.

The safety filter successfully detected crisis-related messages and returned a safer emergency-support response.

## Important Note

This chatbot is for educational purposes only.

It is not a therapist, doctor, counselor, or crisis support service.

It should not be used as a replacement for professional mental health care.

If someone is in immediate danger or thinking about self-harm, they should contact emergency services or a crisis helpline immediately.




```
```
