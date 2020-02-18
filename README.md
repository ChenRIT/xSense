# Commonsense Knowledge Bases and Hotel QA dataset for xSense

## HotelQA:
HotelQA(HotelQA.json) is an adversarial QA dataset of 757 data entries where each question requires commonsense reasoning in the hospitality domain to answer. Similar to [SQUAD v1.1](https://rajpurkar.github.io/SQuAD-explorer/), each data entry of HotelQA  is  a  tuple (review, question, answer) where each answer is a sentence span within the review. On average, each review has 138.6 words, each question has 5.8 words, and each answer has 19.6 words. 

## Commonsense knowledge bases:

LaptopSense (laptopSense.csv), RestaurantSense (restaurantSense.csv) and HospitalitySense (hospitalitySense.csv) contain our collected commonsense knowledge for the laptop, restaurant, and hospitality domain respectively. Each knowledge piece represents an entailment relationship between a premise and a conclusion (e.g., a sharp screen entails an amazing tablet). In each csv file, we store such knowledge in the format of (premise modifier, premise aspect, conclucion modifier, conclusion aspect, confidence), where confidence represents the quality of a knowledge entry. For example, "a sharp screen entails an amazing tablet" is stored as (sharp, screen, amazing, tablet, 0.5278). The sizes of LaptopSense, RestaurantSense and HospitalitySense are 6867, 7546, and 6776 respectively.
