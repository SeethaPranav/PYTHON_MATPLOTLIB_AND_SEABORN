# PYTHON_MATPLOTLIB_AND_SEABORN

# Data visualization using Matplotlib and Seaborn to create insightful charts and plots. 

# 1. Create a line plot using matplotlib pyplot that displays the population of four different cities over time. Each city should have its own line, and the x-axis should represent years (e.g. 2010, 2011, 2012, etc.) while the y-axis should represent the population.The data for the four cities is provided below: 
# •	City A: [500000, 550000, 600000, 650000, 700000, 750000, 800000] 

# •	City B: [800000, 850000, 900000, 950000, 1000000, 1050000, 1100000] 

# •	City C: [1000000, 1050000, 1100000, 1150000, 1200000, 1250000, 1300000] 

# •	City D: [1200000, 1250000, 1300000, 1350000, 1400000, 1450000, 1500000]

import matplotlib.pyplot as plt

years = [2010, 2011, 2012, 2013, 2014, 2015, 2016]

city_a_population = [500000, 550000, 600000, 650000, 700000, 750000, 800000]

city_b_population = [800000, 850000, 900000, 950000, 1000000, 1050000, 1100000]

city_c_population = [1000000, 1050000, 1100000, 1150000, 1200000, 1250000, 1300000]

city_d_population = [1200000, 1250000, 1300000, 1350000, 1400000, 1450000, 1500000]

plt.plot(years, city_a_population, label='City A', marker='o')

plt.plot(years, city_b_population, label='City B', marker='o')

plt.plot(years, city_c_population, label='City C', marker='o')

plt.plot(years, city_d_population, label='City D', marker='o')

plt.xlabel('Year')

plt.ylabel('Population')

plt.title('Population of Cities Over Time')

plt.legend()

plt.grid(True)

plt.figure(figsize=(8, 5), dpi=100)

plt.show()

![q1](https://github.com/user-attachments/assets/e2b2a631-c093-4d20-b5cd-2b564eaf2483)

# 2. Create a scatter plot using seaborn that shows the relationship between the number of hours studied and the test scores obtained by a group of students. Use the following data:
# •	Hours Studied: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
# •	Test Scores: [93, 57, 61, 54, 51, 53, 87, 81, 83, 85]

import seaborn as sns

import pandas as pd

hours_studied = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

test_scores = [93, 57, 61, 54, 51, 53, 87, 81, 83, 85]

data = pd.DataFrame({
    'Hours Studied': hours_studied,
    'Test Scores': test_scores
})

sns.scatterplot(data=data, x='Hours Studied', y='Test Scores')

plt.xlabel('Hours Studied')

plt.ylabel('Test Scores')

plt.title('Relationship Between Hours Studied and Test Scores')

plt.figure(figsize=(8, 5), dpi=100)

plt.show()

![q2](https://github.com/user-attachments/assets/169ed4ea-2b43-44c3-8844-5ada8f87b4ff)

# 3. Create a bar chart using matplotlib pyplot that shows the total sales for each month of the year. Use the following data: 
# •	Month: ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"] 
# •	Sales: [11860, 10480, 4997, 5523, 13965, 6011, 13158, 9533, 5158, 9058, 11346, 6675]

months = ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"]

sales = [11860, 10480, 4997, 5523, 13965, 6011, 13158, 9533, 5158, 9058, 11346, 6675]

plt.bar(months, sales, color='skyblue')

plt.xlabel('Month')

plt.ylabel('Sales ($)')

plt.title('Total Sales for Each Month of the Year')

plt.figure(figsize=(8, 5), dpi=100)

plt.show()

![q3](https://github.com/user-attachments/assets/40101861-7f72-43e7-9b31-86ee45742072)




