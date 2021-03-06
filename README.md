# emotion-detection

1.	The code is written in Jupyter notebook, and so to be able to run it you need to have it installed. Refer to this guide on how to install it: https://jupyter.org/install

2.	Before running the project you need to update two lines in the first cell of the Jupyter notebook titled "Imports, path and bearer token". Otherwise, the first half of the project will not be able to run.

2a.	Change the path variable on line 47 to the path value of wherever your notebook and downloaded datasets are. Ensure that they are in the same folder. This project will not run if you don’t do this.

2b.	To be able to run this project in its fullness you need to set up a Twitter Developer account and acquire a bearer token to be able to fetch the tweets. After this is done, uncomment the line 49 and type your bearer token between the quotation marks. This project will run without doing this, but you will not be able to fetch the dataset yourself.

2c.	Several cells in the Jupyter notebook are responsible for fetching the datasets and performing different actions on them. These take time and so you can skip some of them (but not all). As you read through the notebook you will see a comment that repeats itself in the code several times that says “# run below to read dataset into variable”. You can search for this line by pressing Ctrl+F together and typing in that line. It will refer you to cells that need to be run to read different versions of the datasets so you can perform preprocessing and classification actions. The datasets versions that ae available to you are: hydrated tweets for each month (e.g. “2en_2april_dataset_2.csv”), raw training dataset (“td_trial2.csv”), training dataset with segmented hashtags (“clean_td.csv”), preprocessed training dataset (“final_training_dataset.tsv”), preprocessed COVID-19 dataset (“preprocess_covid_dataset.csv”), and COVID-19 dataset labelled with emotions (“labelled_all_months.csv”).
