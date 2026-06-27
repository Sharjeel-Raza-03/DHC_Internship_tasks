# General Health Query Chatbot

## Project Overview

This project is part of the DevelopersHub AI/ML Engineering Internship.

The goal of this task is to build a simple health-related chatbot that can answer general health questions in a safe, friendly, and clear way.

The chatbot uses prompt engineering and safety filters to avoid harmful medical advice.

## Objective

Create a chatbot that answers general health-related questions while following safety rules.

## Task Requirements

The chatbot should:

* Answer general health questions
* Use prompt engineering
* Respond in a friendly and clear tone
* Avoid giving diagnosis
* Avoid prescribing medicine
* Avoid giving exact dosage instructions
* Redirect emergency cases to medical professionals or emergency services

## Example Questions

```text
What causes a sore throat?
Is paracetamol safe for children?
How can I prevent dehydration?
What are common symptoms of flu?
```

## Libraries Used

```text
openai
pandas
getpass
os
```

## Project Steps

1. Installed required libraries
2. Imported necessary packages
3. Added API key setup
4. Created an OpenAI client
5. Designed a system prompt
6. Created emergency and high-risk keyword lists
7. Built a safety filter
8. Created a chatbot response function
9. Tested the chatbot with example questions
10. Tested emergency and high-risk cases
11. Created a simple chat loop
12. Saved chatbot test results into a CSV file

## Safety Features

The chatbot includes safety filters for:

```text
Emergency symptoms
Medication dosage questions
Child medication questions
Pregnancy-related questions
Chronic illness questions
Self-harm or urgent health situations
```

If an emergency-related query is detected, the chatbot advises the user to seek emergency medical help immediately.

## Prompt Engineering

A system prompt was designed to make the chatbot:

```text
Friendly
Clear
Safe
Non-diagnostic
Educational
Supportive
```

The chatbot is instructed not to diagnose diseases, prescribe medicines, or replace a doctor or pharmacist.

## Model Used

```text
OpenAI GPT model
```

A no-API rule-based version can also be used for testing if an API key is not available.

## Output

The chatbot can respond to general health queries and provide safe educational information.

Example:

```text
User: What causes a sore throat?

Bot: A sore throat can be caused by viral infections, allergies, dry air, smoke, or irritation. If symptoms are severe or last for several days, consult a doctor.
```

## Results

The chatbot successfully answered general health questions.

The safety filter detected emergency and high-risk queries.

The chatbot avoided giving unsafe medical advice such as diagnosis, prescriptions, or exact medication dosage.

## Important Note

This chatbot is for educational purposes only.

It is not a doctor, pharmacist, emergency service, or medical professional.

It should not be used for medical diagnosis, treatment, or emergency care.

For serious symptoms, users should contact a qualified healthcare professional or emergency services.

