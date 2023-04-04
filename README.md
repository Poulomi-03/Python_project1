# Python_project1
 #Plots a straight line graph between product category and sales against each of the products .
import numpy as np
import matplotlib.pyplot as plt
product_category=np.array(['Furniture','Technology','Office Supplies'])
sales=np.array([4110451.90,4744557.50, 3787492.52])
#plt.bar(product_category,sales)
#plt.show()
plt.plot(product_category,sales)
#plt.show()
plt.title(" Retailer graph ")

# labeling axes
plt.xlabel("product_category")
plt.ylabel("sales")

# necessary command to display the created graph
plt.show()
