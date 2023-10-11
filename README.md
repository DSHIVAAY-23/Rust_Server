# Rust_Server
Rust server Actix.
This is a Rust web server built using the Actix framework and integrates with Amazon DynamoDB for data storage. It provides a template for building web services and interacting with DynamoDB tables. This README provides an overview of the project, how to set it up, and how to use it.

Prerequisites
Before you begin, ensure you have the following installed on your system:

Rust
Cargo
DynamoDB (if you plan to use AWS DynamoDB)

Configuration

Before running the server, you need to set up your environment variables and configuration. You can do this by creating a .env file in the project root:

env

# Actix Server Configuration
SERVER_HOST=127.0.0.1
SERVER_PORT=8080

# AWS DynamoDB Configuration
AWS_REGION=your-aws-region
AWS_ACCESS_KEY_ID=your-access-key-id
AWS_SECRET_ACCESS_KEY=your-secret-access-key
DYNAMODB_TABLE_NAME=your-dynamodb-table-name

Running the Server

To start the Actix server, run the following command:

cargo run

The server will start on the specified host and port, and it will be ready to receive HTTP requests.







