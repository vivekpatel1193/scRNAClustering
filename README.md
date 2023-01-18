# scRNAClustering

Single Cell RNA Clustering Competition

Final Competition - Team Underdogs

Prerequisites:

Any python notebook, preferably Jupyter Notebook. Running Python 3.0 Libraries: Numpy, Pandas, Scikit-Learn, Matplotlib, Seaborn

OS: Windows 10

How to execute:

Place the files "data_tr.txt", "gene_names.txt", "data_ts.txt" in the same folder as the notebooks.

Open first notebook named "Competition Preprocessing", it is well organized to be run step by step in Jupyter. It also has comments explaining what is going on in the cell below. The notebook generates a CSV file named "final_features.csv" which is the preprocessed data that can be used to train models.

The notebook also tests three models KMeans, Birch and Spectral Clustering and displays the silhouette score.

If using Jupyter Notebook, simply run each cell or click "Run-All"

The notebook named "Final Evaluation" was the one used for evaluating the final leaderboard score. It uses Birch.
