# Customer-Segmentation
This project makes use of K-Means clustering based on income and spending behaviour, and links it to the average age of each of the clusters. 

#### Sources used:
The data used is a part of a dataset of mall customers. <br>
Dataset link: https://www.kaggle.com/datasets/shrutimechlearn/customer-data 

#### Methodology 
<ul>
  <li>Used K-means on both 2D and 3D data.</li>
  <li>Features used: Annual Income, Spending Score, and Age.</li>
  <li>Scaled data using a Standard Scaler.</li>
  <li>Found:</li>
  <ol>
    <li>Younger customers belong to low income, high spending group.</li>
    <li>Older customers belong to low income, low spending group.</li>
    <li>Customers around thirty belong to high income, high spending group.</li>
    <li>Customers around forty belong to high income, low spending group.</li>
  </ol>
  <li>Evaluated Silhouette Coefficients of the samples to determine the number to clusters.</li>
</ul>
