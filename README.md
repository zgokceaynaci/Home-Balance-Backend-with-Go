# Home-Balance-Backend-with-Go
This is the backend service for **HomeBalance**, built with Go. It manages API requests, data storage, and communication with Firebase and PostgreSQL.

## Features
- Secure API for expense and task management
- Integration with Firebase for authentication
- PostgreSQL database for data storage

## Technologies Used
- Go
- Firebase
- PostgreSQL

## Getting Started

### Prerequisites
- [Go](https://go.dev/dl/) installed
- A PostgreSQL database set up
- A Firebase account

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/zgokceaynaci/Home-Balance-Backend-with-Go.git
   cd Home-Balance-Backend-with-Go
   
2. Set up environment variables:
   - Create a .env file in the root directory and add the following:
     ```bash
     FIREBASE_API_KEY=your_firebase_api_key
     DATABASE_URL=your_postgresql_connection_url

3. Install dependencies:
   ```bash
   go mod tidy
   
4. Run the server:
   ```bash
   go run main.go
  


   
