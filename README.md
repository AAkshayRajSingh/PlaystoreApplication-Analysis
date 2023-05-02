# Steps for working ofusing a machine learning to Analyse User perceptions and Data Analysis on Google playstore app reviews.

Download the .ipynb file and save in the local.
1.Go to https://colab.research.google.com/ or Jupyter Notebook to access the Google Colab / Jupyter notebook website.
2.Click the "File" button in the upper left corner of the screen.
3.Choose "Upload notebook" from the selection list.
4.Select thedownloaded .ipynb file from your local computer to upload.
5.Wait for the file to upload before clicking on it to open it in Google Colab.
Once you've opened the.ipynb file in Google Colab, you can upload your dataset file by doing the following:

Once you have the .ipynb file open in Google Colab/Jupyter, you can upload your dataset file by following these steps:

1.Click on the "Files" icon on the left side of the screen
2.Click on the "Upload" button and select your dataset file from your local computer (Googleplaystore.csv and google_user_review.csv).
3.Wait for the file to upload, and then you should see it in the list of files in the "Files" tab.

Now that you have uploaded your dataset file, you can use it in your .ipynb file by specifying the file path to access it. For example, if you uploaded a file called "googleplaystore.csv", you can load it into a Pandas dataframe with the following code:

import pandas as pd

df = pd.read_csv('/content/googleplaystore.csv')

Once you have uploaded both the .ipynb file and the dataset file to Google Colab and ensured that the dataset file is accessible in the .ipynb file, you can run the code in the notebook by following these steps:

1.Click on "Runtime" in the top menu
2.Select "Run all" from the dropdown menu
3.Alternatively, you can run each cell in the notebook individually by clicking on the play button (triangle) next to each cell or using the shortcut key "Shift + Enter".

When you run the cells, the code will execute and the outputs will be displayed in the notebook. You can interact with the notebook by modifying the code, adding new cells, or inserting comments. Additionally, you can save the changes to the notebook and the output cells by clicking on "File" in the top menu and selecting "Save" or "Save a copy in Drive".


And You should see all the reults and plots coded for the ser perceptions and Data Analysis on Google playstore app reviews.
