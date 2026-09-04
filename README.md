<img width="1599" height="899" alt="image for project" src="https://github.com/user-attachments/assets/ff4e2c74-80f4-460d-93e8-7eb5318d0a09" />

# Zomato Restaurant Analysis - Delhi NCR

## Overview
Exploratory Data Analysis on 1,965 restaurants across Delhi NCR 
using Python. The analysis uncovers trends in ratings, pricing, 
locality patterns and hidden gems.

## Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook

## Dataset
Kaggle - Zomato Delhi NCR Restaurants Dataset

## Questions Explored
1. Most reviewed restaurant per locality
2. Locality with most retaurants
3. Rating distribution per locality
4. Gap between dining and delivery rating
5. Price distribution per locality
6. Relationship between pricing and dining rating

## Key Insights
- Plum by Bent Chair located in Aerocity, New Delhi is the most reviewed restaurant in Delhi NCR
- Connaught Place has the highest restaurant density in Delhi NCR
- Average dining rating is 4.14 across all localities
- Dining experience significantly outperforms delivery ratings
- No strong correlation between price and rating
- Hidden gems exist in residential areas with high ratings but low reviews

## Power BI Dashboard

### Page 1 
<img width="1310" height="725" alt="Screenshot 2026-09-04 105808 - Copy - Copy" src="https://github.com/user-attachments/assets/c5ce1c8c-0aa8-4f1a-8570-bc747dfeb0e8" />

Connaught Place leads with the highest restaurant density and average dining rating across all restaurant in Delhi is 4.10 with Open Tap having the highest dining rating of 4.53

### Page 2
<img width="1317" height="734" alt="Screenshot 2026-09-04 105825" src="https://github.com/user-attachments/assets/179cfe7e-d6a0-4c8b-ae43-2adc0e5babcd" />

North Indian dominates as most common cuisine
### Page 3 
<img width="1307" height="726" alt="Screenshot 2026-09-04 105838" src="https://github.com/user-attachments/assets/e5c979e8-b9c1-4ea0-be12-0ba042a0c1c1" />

Dining ratings (4.14) significantly higher than delivery (3.15). 
Three restaurants The big chill, Kuremal Mohan Lal Kulfi wale, and Dum Pukht has the biggest gap between dining and delivery rating
### Page 4 
<img width="1313" height="737" alt="Screenshot 2026-09-04 105853 - Copy" src="https://github.com/user-attachments/assets/33c35378-4c91-4bba-ba80-1c289e2adde5" />

Two new measures created:
- Value Score= rating/ (price/1000) finds best value restaurants
- Gem Score= rating * (1/review count) finds underrated restaurants
  
Cool Point Shahi Tukda is the best value restaurant 
Echoes Living Room is the most underrated restaurant

## Project Structure
- `zomato_eda.ipynb` - Main analysis notebook
- `zomato_cleaned.csv` - Cleaned dataset
- `DelhiNCR Restaurant.csv` - Raw dataset
