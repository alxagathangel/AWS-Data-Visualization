# Data Visualization using AWS
For this project, I have utilized the Amazon S3 Service, as well as QuickSight to visualize statistics regarding Netflix titles. 

## Approach
We begin by breating an S3 bucket. There, we add two objects via upload: a .csv file containing our dataset & a .json file. After the initial upload, I'm changing the URI to the S3 URI of the bucket and reupload. This edit is important, since the file needs to have the correct location.
The S3 Bucket now has two objects. This bucket serves as our Dataset.
![step1](https://github.com/user-attachments/assets/71617faa-f538-4dd1-bdef-7975165472f3)

After Signing in to QuickSight, we connect to the S3 bucket. Here, we add the table of interest (kaggle-netflix-data) as well as the URL to the manifest file. Uploading the .json file is important, because it essentially "tells" QuickSight how to process the data. It shows how the data is formatted, hence how it should be presented.
![step3](https://github.com/user-attachments/assets/c6fafe2f-cd63-4a43-8ec6-de1763af61f8)
After this step, we are ready to visualize.

The following Graphs have been created using the QuickSight features: 
1. Number of Movies/TV Shows by Release Year, using a donut chart
2. Number of Movies VS TV Shows by Release Year, using a horizontal 100% stacked chart.
3. Number of Titles Added by Data, using a horizontal chart.
4. Number of Titles by Release Year and Type, using a table.
5. Number of Thrillers, TV Comedies, Action & Adventure, using a donut chart.
6. Number of Thrillers, TV Comedies, Action & Adventure released after 2015, using a donut chart.
![visuals](https://github.com/user-attachments/assets/0acde02b-8197-4972-9853-9aa755b7564e)
