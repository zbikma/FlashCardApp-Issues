# FlashCardApp Issue Tracker

Welcome to the public issue tracker for the FlashCardApp. Please use this repository to report bugs, request features, and track the development of the app.

## Reporting Issues
- If you encounter any bugs or issues, feel free to open a [new issue](https://github.com/zbikma/FlashCardApp-Issues/issues/new).
- For feature requests, you can also use the [issues tab](https://github.com/zbikma/FlashCardApp-Issues/issues/new).

Please provide as much detail as possible to help us understand and resolve the issue.

**Note:** This repository is for issue tracking only. The source code is maintained in a private repository.

# AWS Learning and Serverless FlashCardApp

## About FlashCardApp

FlashCardApp serves as my journey into learning AWS services through practical implementation. What started as an experiment in exploring AWS services has now evolved into a serverless web app where I store notes and continue building more features. The eventual goal is to integrate AI and LLM (Large Language Models) capabilities, allowing me to utilize even more AWS services as the project grows.

### Project Overview

Currently, this project is focused on building a **serverless web application** using several AWS services like **AWS Lambda** for backend functionality and **Amazon S3** for hosting and data storage. Over time, I’ve gained a much better understanding of services like **API Gateway**, which was once quite unclear to me, but now feels more intuitive as I implement them in small proof-of-concept projects.

### Technologies Used

- **AWS Lambda**: Serverless compute service to run backend logic without managing servers.
- **Amazon API Gateway**: A fully managed service to create, publish, and secure APIs for the app.
- **Amazon S3**: Used for static website hosting and as a storage solution for our CSV-based data source.
- **React.js**: The frontend framework used for building the user interface.
- **AWS CloudWatch**: For monitoring, logging, and debugging Lambda functions.
- **JavaScript/Node.js**: Backend development using Node.js for writing Lambda functions.
- **GPT-based Co-programming**: I am working with my custom AI assistant, ZCoder GPT, who helps me in coding tasks by providing suggestions and optimizing productivity.

### Features

- **Flashcard Viewer**: The current web app displays flashcards saved in a CSV file stored in an AWS S3 bucket. Flashcards are categorized by topic, most of which are related to AWS services, as I’m studying for AWS certification.
- **Topic Management**: Flashcards are displayed dynamically based on the selected topic, pulled directly from the CSV file.
  
  > In the future, if the dataset becomes large, we plan to migrate from CSV files to a more scalable **relational database**.

### AWS Services and Frameworks Explained

- **AWS Lambda**: A compute service that lets you run code without provisioning or managing servers. You write functions, define their triggers (like HTTP requests from API Gateway), and AWS takes care of running them.
  
- **Amazon S3**: This service provides scalable object storage, often used for static website hosting and backup solutions. In this project, we use S3 to store flashcards in CSV format, which the application reads dynamically.

- **API Gateway**: A managed service that allows you to create, publish, and manage RESTful APIs to expose backend services like Lambda. It's used here to provide HTTP endpoints for the app's Lambda functions.

- **React.js**: A popular frontend JavaScript library for building user interfaces. It's used here to render the flashcards dynamically based on the AWS Lambda output.

- **CloudWatch**: A monitoring service used to track logs, performance metrics, and alerts for AWS resources. Here, it's useful for debugging Lambda functions.

### Future Plans

- **AI Integration**: As we expand the project, I plan to integrate LLMs for advanced features like note summaries or intelligent study recommendations.
- **Database Migration**: While the project currently relies on a CSV file as the source for flashcards, we plan to migrate to a relational database (such as Amazon RDS) once the dataset grows.
- **More AWS Services**: The project will expand to use additional AWS services such as **AWS DynamoDB** for NoSQL storage or **Amazon RDS** for relational data storage.

### Collaboration with ServerlessWebapp GPT

I co-program with my custom AI assistant, [**ServerlessWebapp GPT**](https://chatgpt.com/g/g-SGZoTjUKC-serverlesswebapp). This GPT model is fine-tuned to work collaboratively, enhancing my coding productivity and serving as a personalized coding partner. What I find fascinating about AI and LLMs is their flexibility in adapting to different tasks, allowing me to create specialized agents for specific project needs.

### Conclusion

This repository is my ongoing learning process, blending AWS services with modern web development practices. The combination of serverless architecture, AI collaboration, and cloud infrastructure makes this an exciting and evolving project.

Feel free to explore the code, contribute, or reach out with any suggestions!


