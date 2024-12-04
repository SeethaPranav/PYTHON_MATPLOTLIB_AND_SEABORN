# PYTHON_MATPLOTLIB_AND_SEABORN

# Data visualization using Matplotlib and Seaborn to create insightful charts and plots. Create a line plot using matplotlib pyplot that displays the population of four different cities over time. Each city should have its own line, and the x-axis should represent years (e.g. 2010, 2011, 2012, etc.) while the y-axis should represent the population.The data for the four cities is provided below: 
•	City A: [500000, 550000, 600000, 650000, 700000, 750000, 800000] 

•	City B: [800000, 850000, 900000, 950000, 1000000, 1050000, 1100000] 

•	City C: [1000000, 1050000, 1100000, 1150000, 1200000, 1250000, 1300000] 

•	City D: [1200000, 1250000, 1300000, 1350000, 1400000, 1450000, 1500000]

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

plt.show()

![q1](https://github.com/user-attachments/assets/00961e7b-d34c-4b1f-a542-de6f89deee9b)


