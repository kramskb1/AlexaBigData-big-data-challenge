# AlexaBigData-big-data-challenge
Created DataFrames to match production-ready tables from two big Amazon customer review datasets. Used the furnished schema to create tables in my RDS database. Created two separate Google Colab notebooks and extracted two datasets from the list at review dataset, one into each notebook. I decided to analyze the video games dataset and the musical instruments dataset. I found it easier to work with these S3 data sources in two separate Colab notebooks.

I was sure to handle the header correctly. If I read the file without the header parameter, I may have found that the column headers are included in the table rows. For each notebook, I counted the number of rows in the dataset. I transformed the dataset to fit the dataset in the Schema file. I made sure that the DataFrames matched in data type and in column name. I loaded the DataFrames that corresponded to tables into an RDS instance. I was aware that this process could take up to 10 minutes for each. I made sure that everything was correct before uploading.

I showed the data for video games in my Colab file. I showed the count of the data which was 1,785,997. In SQL, I found the count of the number of products, which was 65,792. I printed the schema. I transformed the dataframe to fit the data review table. The columns I was interested in were review_id, customer_id, product_id, product_parent, and review_date. I dropped the duplicates. I transformed the dataframe to fit the products table. I dropped the duplicates and printed the schema. I transformed the dataframe to fit the customers table. I found the count of each customer id. I transformed the dataframe to fit the vine table. 
	
Out of the video games that I showed there were mixed reviews. Thrustmaster and Tonsee 6 Buttons were popular. Zero Suit Samus was good. Geltabz Performance was average. Hidden Mysteries was not popular. 

I showed the data for musical instruments in my other Colab file. I showed the count of the data which was 904,765. I printed the schema. I transformed the dataframe to fit the data review table. The columns I was interested in were review_id, customer_id, product_id, product_parent, and review_date. I dropped the duplicates. I transformed the dataframe to fit the products table. I dropped the duplicates and printed the schema. I transformed the dataframe to fit the customers table. I found the count of each customer id. I transformed the dataframe to fit the vine table.

Out of the musical instruments that I showed there were mixed reviews. Sennheiser, Hohner, and Blue Yeti were popular. AGPtek and AudioQuest were average. By looking at the vine_df there were a decent amount of instruments that did not have any votes. Therefore, the helpful votes column might be a bit misleading in determining how popular a specific musical instrument is. 

I learned a lot about using big data while completing this assignment. I learned how to use a Google Colab notebook. I learned how to use PySpark. I learned how to use an AWS Relational Database. I feel like these skills are very helpful to know in today’s job market, and I feel like completing this assignment makes me more qualified to use these skills in the workplace. 






