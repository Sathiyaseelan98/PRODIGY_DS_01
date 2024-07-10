# PRODIGY_DS_01
Visualizing the Distribution of Genders (Categorical Variable) 
import matplotlib.pyplot as plt


genders = ['Male', 'Female', 'Non-Binary', 'Other']
counts = [300, 350, 50, 20]  # Example counts for each gender category


plt.figure(figsize=(8, 6))
plt.bar(genders, counts, color=['blue', 'pink', 'green', 'orange'])
plt.xlabel('Gender')
plt.ylabel('Count')
plt.title('Distribution of Genders in the Population')
plt.grid(axis='y', linestyle='--', alpha=0.7)
plt.show()
