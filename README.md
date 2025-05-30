# USA-Real-Estate-Market-Analysis
Uncovering insights from 2.2 M+ listings across states

Hi, I’m Abu Sufian, and in this project, I dove deep into the 2024 U.S. real estate market to uncover hidden patterns, regional pricing dynamics, and what really drives home values in different parts of the country.  

If you're a **homebuyer**, **investor**, or simply a **data enthusiast**—this analysis will give you a clearer picture of where value lies, which cities are booming, and how you can make more informed property decisions using data.

---

## Why I Did This Project

I’ve always been fascinated by real estate trends—how the same house can cost $200K in one city and $2M in another. So I asked myself:  
**What makes one home more valuable than another?**  
Is it the size? The number of beds? The location? Or something else?

To find the answers, I used Python, Pandas, Seaborn, and Matplotlib to clean, explore, and visualize thousands of property listings across the U.S.

---

## What You'll Learn from This Project

- Which states and cities are the most (and least) expensive to buy a home  
- Whether **bedrooms** or **bathrooms** affect pricing more (spoiler: it’s not what most people think!)  
- Which ZIP codes offer surprising value—and which are overpriced  
- How to measure home value using new engineered features like **price per sqft**, **acre per bedroom**, and more  

---

## Key Analyses (with Real Insights)

Here are the major analyses I performed and the stories the data told me:

### 1. Average Property Price by State  
Hawaii leads with an average price of ~$1.4M—no surprise given its paradise appeal. But the Virgin Islands, California, and New York aren’t far behind.  
<img width="395" alt="Image" src="https://github.com/user-attachments/assets/136170df-27bb-421b-9e96-cc7f787ee4ca" />

### 2. Top 10 Cities with Highest Median Prices  
Cities like **Rancho Santa Fe** ($4.97M) and **Malibu** ($3.97M) top the charts. These aren’t just cities—they’re luxury destinations.  
<img width="486" alt="Image" src="https://github.com/user-attachments/assets/d94a2243-e183-4831-a0b4-480c98002aa9" />

### 3. Home Size Distribution  
Most homes fall between 1,000–3,000 sqft, which seems to be the sweet spot for American living.  
<img width="474" alt="Image" src="https://github.com/user-attachments/assets/f7d62b03-6df0-4489-9d6d-32c88af6a2a6" />

### 4. Beds vs. Price  
Yes, more bedrooms mean a higher price—but not always. The relationship is not perfectly linear.  
<img width="429" alt="Image" src="https://github.com/user-attachments/assets/0351813b-4148-4c02-8b1a-3595cf41a723" />

### 5. Bathrooms vs. Price — The Real Influencer  
Here’s something interesting: **Bathrooms affect price more than bedrooms.**  
Even with the same number of beds, homes with more baths are consistently more expensive.  
*If you’re renovating, consider adding a bathroom over a bedroom!*

<img width="410" alt="Image" src="https://github.com/user-attachments/assets/5fb69b81-4990-4bdf-b698-04b61991b6cb" />

### 🌾 6. Acre Lot Size vs. Price  
Larger lots = higher price? Not always. This varies drastically by state.  
➡️ *Scatter plot to visualize spread*

### 🔥 7. Correlation Heatmap  
Strongest price correlations?  
- `house_size` → 0.62  
- `bath` → 0.54  
➡️ Bedrooms? Much less important than I thought.

### 📍 8. Most Common ZIP Codes  
By finding ZIPs with the most listings, I could identify real estate hot zones.  
➡️ *Donut chart showing listing density*

### 🏷️ 9. State-wise Price Category Breakdown  
I divided listings into three tiers: **affordable**, **mid-range**, and **luxury**.  
California unsurprisingly leads in luxury homes, but states like Florida and Texas offer tons of affordable properties.  
➡️ *Stacked bar chart*

### 📦 10. Price Distribution by State  
California has a massive price range—million-dollar homes next to mid-range ones.  
➡️ *Boxplot showing price variation*

---

## 🛠️ Feature Engineering: Making Raw Data Smarter

Sometimes raw data isn’t enough. I created new features to get deeper insights:

- **Price per Sqft** – A better way to compare value across cities  
- **Is_Luxury_Home** – A binary tag for homes priced above $1M  
- **Bedroom/Bathroom Ratio** – Tells us how balanced a home layout is  
- **Acre per Bedroom** – Helps evaluate land usage efficiency

---

## 🌟 Bonus Visualization

### 🏙️ Average Price per Sqft in Top 10 Cities  
This chart shows where every square foot really costs you—NYC, LA, and Miami lead the pack.  
➡️ *Lollipop chart that visually pops*

---

## 📌 Real-World Takeaways

Here’s what this analysis taught me (and hopefully you too):

- 📍 **Location** is still king in real estate  
- 🛁 **Bathrooms matter more than bedrooms** when it comes to price impact  
- 🗺️ **ZIP codes reveal hidden gems**—some affordable, some overpriced  
- 🏖️ **California dominates the luxury market**, but **Florida is full of value**

---

## 📂 Dataset Details

- Name: **USA Real Estate Dataset (2024)**  
- Source: [Kaggle Dataset](#) *(replace with your link)*  
- Rows: ~30,000 listings  
- Key columns: `price`, `bed`, `bath`, `acre_lot`, `house_size`, `city`, `state`, `zip_code`

---

## ✨ What’s Next?

This project was focused on exploration and storytelling.  
Next steps could include:

- Building **price prediction models (ML)**  
- Creating a **recommendation engine** for property hunters  
- Combining with external data like crime rates or school ratings

---

## 🧑‍💻 About Me

I'm **Abu Sufian**, a data analyst passionate about using data to solve real-world problems.  
If you enjoyed this project or want to collaborate—let’s connect!

🔗 [LinkedIn](https://linkedin.com/in/yourprofile)  
📧 youremail@example.com  
📊 [My Portfolio](https://github.com/yourusername)

---

> **“Real estate is not just about land and buildings. It’s about people, patterns, and possibilities. And data helps us see that.”**

