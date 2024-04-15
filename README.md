Cleaned data csv  has all the necessary columns, with no missing values.
Encoded data is stored in an numpy array: data_df_transformed
For GNN model, the data will be finally stored in a pytorch Data Object
Now we have the nodes(data_df_transformed being transformed from numpy array to a torch tensor)
But don't have the edges information(to be created using the Neighbors columns)

