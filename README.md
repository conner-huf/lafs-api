# UPDATE:
I've deployed this project using AWS. Some of the things I've experimented with / used in this project are:

- Containerization with Docker
- AWS Lambdas
- EC2
- S3
- Angular
- Writing APIs

The deployed project can be found [here](http://connerbucket1.s3-website-us-east-1.amazonaws.com/)

Below is a screenshot of the landing page:
![home page](screenshots/homePage.png)

There, you can click on the "Angular" section to be taken to the question page:
![question page](screenshots/questionPage.png)

The questions are filled using json data, which is pulled from DynamoDB. Each question has a unique key that is matched with an answer's unique key in DynamoDB to provide the answers to the questions. You can click on a question to see the question's answers:
![answer page](screenshots/answerPage.png)
