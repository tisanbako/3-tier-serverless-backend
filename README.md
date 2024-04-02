# Three-Tier Architecture with Serverless Backend 

This project demonstrates the implementation of a Three-Tier Architecture with a Serverless Backend, leveraging various AWS services to create a scalable and efficient system.
![alt text](https://github.com/tisanbako/3-tier-serverless-backend/blob/main/e-tier-serverless.gif)

# Components Utilized

- **EC2** 🖥️: Powers the frontend of the application. JavaScript is used to build the user interface and interact with the backend.
- **API Gateway** 🌐: Facilitates communication between the frontend and backend. It acts as a bridge for routing requests to Lambda functions.
- **AWS Lambda** 🔥: Backend functionality is implemented using Python Lambda functions. These functions handle POST and GET actions.
- **DynamoDB** 💾: Serves as the database for storing all data. DynamoDB's scalability and performance make it suitable for various application needs.

## Architecture Overview

1. **Frontend (EC2)**:
   - Hosts the user interface of the application.
   - Developed using JavaScript to provide a responsive and interactive experience.

2. **API Gateway**:
   - Acts as a centralized entry point for API requests.
   - Routes requests to appropriate Lambda functions based on configured endpoints.

3. **Backend (AWS Lambda)**:
   - Python Lambda functions handle backend logic, including processing POST and GET actions.
   - Serverless architecture eliminates the need for managing server infrastructure, providing scalability and cost-efficiency.

4. **DynamoDB**:
   - NoSQL database used for storing application data.
   - Offers seamless scalability and low-latency access, ensuring optimal performance for the application.

## Benefits

- **Scalability**: The serverless architecture allows for seamless scalability, automatically adjusting resources based on demand.
- **Cost-Efficiency**: With serverless computing, you only pay for the resources consumed during execution, reducing operational costs.
- **Low Maintenance**: Eliminates the need for server maintenance tasks, allowing developers to focus on building and improving the application.
- **High Performance**: DynamoDB's low-latency access ensures fast response times, enhancing the user experience.

## Usage

1. Clone the repository to your local machine.
2. Deploy the frontend on an EC2 instance.
3. Set up API Gateway to route requests to Lambda functions.
4. Deploy Lambda functions to handle backend logic.
5. Configure DynamoDB tables for data storage.
6. Update configuration files as necessary.
7. Test the application to ensure proper functionality.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to fork the repository and submit a pull request with your changes.



