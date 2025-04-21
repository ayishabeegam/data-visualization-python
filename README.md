# data-visualization-python
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd

years = [2010, 2011, 2012,2013,2014,2015,2016]
City_A = [500000, 550000, 600000, 650000, 700000, 750000, 800000]
City_B = [800000, 850000, 900000, 950000, 1000000, 1050000, 1100000]
City_C = [1000000, 1050000, 1100000, 1150000, 1200000, 1250000, 1300000]
City_D = [1200000, 1250000, 1300000, 1350000, 1400000, 1450000, 1500000]


plt.plot(years, City_A, label='City A',color='r')
plt.plot(years, City_B, label='City B')
plt.plot(years, City_C, label='City C')
plt.plot(years, City_D, label='City D')


plt.xlabel('Year')
plt.ylabel('Population')
plt.title('Population Growth of Four Cities')
plt.legend()
plt.show()



pip install seaborn
import seaborn as sns
Hours = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
Test_Scores = [93, 57, 61, 54, 51, 53, 87, 81, 83, 85]
plt.title('marks based on hours studied')
sns.scatterplot(x=Hours, y=Test_Scores)
plt.show()






import matplotlib.pyplot as plt
import numpy as np
import pandas as pd

Month = ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"]
Sales = [11860, 10480, 4997, 5523, 13965, 6011, 13158, 9533, 5158, 9058, 11346, 6675]

plt.bar(Month,Sales)
plt.xlabel('Month')
plt.ylabel('Sales')
plt.title('sales report')
plt.legend()
plt.show()

