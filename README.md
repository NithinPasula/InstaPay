# InstaPay

InstaPay is a basic version of a payment application similar to PayTM. It provides a platform for users to make transactions seamlessly.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- User Authentication
- Transaction History
- Secure Payments
- User-Friendly Interface

## Technologies Used

- **Frontend**: JavaScript, HTML, CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Containerization**: Docker

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

- Node.js
- Docker (optional)

### Installation

1. Clone the repository:

   git clone https://github.com/NithinPasula/InstaPay.git

2. Navigate to the project directory:
  cd InstaPay

## Usage
### Running the Application

1. Navigate to the backend directory and install dependencies:

   cd backend
   npm install
   
2. Start the backend server:

   npm start

3. Navigate to the frontend directory and install dependencies:

   cd ../frontend
   npm install

4. Start the frontend server:

   npm start

## Using Docker

1. Build the Docker image:

   docker build -t instapay .

2. Run the Docker container:

  docker run -p 3000:3000 instapay

### Contributing

Contributions are what make the open source community such an amazing place to be, learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request

### License

Distributed under the MIT License. See LICENSE for more information.



