# smart-photo-album

# Overview
This project created a smart photo album that shows pictures based on the query by the user. 
It gives search and upload functionality, 'upload' is to add photos to the database and 'search' is to search for matching photos from the database.
We have also integrated voice based input query to the user.

# Details

The backend of the project is driven through AWS services
We used AWS lambda, API Gateway, rekognition, Lex,ElasticSearch for the implementation.

We also eveloped a CloudFormation Stack that can deploy the resources based on a single template file. 

A codepipeline pipeline was also developed so that changes made in the git repo would directly be seen on the lambda codes.
