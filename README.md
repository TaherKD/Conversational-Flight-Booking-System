# Conversational-Flight-Booking-System
Making a conversational flight-booking system, which can show relevant flights when given a natural-language query.

## Problem 
Even though textual data is widely available, the complexity of natural language makes it extremely difficult to extract useful information from text. In this session, you’ll learn to build an Information Extraction (IE) system that can extract structured data from unstructured textual data. A key component in information extraction systems is Named-Entity-Recognition (NER).

Let’s say you are making a conversational flight-booking system, which can show relevant flights when given a natural-language query such as “Please show me all morning flights from Bangalore to Mumbai on next Monday.” For the system to be able to process this query, it has to extract useful named entities from the unstructured text query and convert them to a structured format, such as the following dictionary/JSON object: 

{source: 'Bangalore', 
destination: 'Mumbai',
day: 'Monday', 
time-of-day: 'morning'}

Using these entities, you could query a database and get all relevant flight results. In general, named entities refer to names of people, organizations (Google), places (India, Mumbai), specific dates and time (Monday, 8 pm) etc.

I built such system which can extract structured information from unstructured text data. In the process, I learned the concepts mentioned below - 
1. Named Entity Recognition
2. I-O-B labels
3. Building models for Entity Recognition
4. Rule-based techniques
5. Regular expression based techniques
6. Chunking
7. Probabilistic models
8. Unigram & Bigram models
9. Naive Bayes Classifier
10. Decision trees
11. Conditional Random Fields (CRFs)

## Data
We’ll use the ATIS (Airline Travel Information Systems) dataset to build an IE system. The ATIS dataset consists of English language queries for booking (or requesting information about) flights in the US.
