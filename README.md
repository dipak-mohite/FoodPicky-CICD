Here’s the README file with the requested social media icons and profile links:

```markdown
# FoodyPicky

FoodyPicky is a comprehensive food ordering system designed to streamline the process of menu browsing, order placement, and payment processing. The system includes user authentication, real-time order management, status tracking, and automated notifications. Deployed on AWS Cloud Infrastructure, FoodyPicky offers enhanced scalability and reliability, utilizing CI/CD pipelines for efficient and reliable software delivery.

## Features

- **User Authentication**: Secure login and registration system for users.
- **Real-time Order Management**: Manage and track orders in real-time.
- **Status Tracking**: Keep users informed with live order status updates.
- **Automated Notifications**: Send notifications for order confirmations and updates.
- **User-Friendly Interface**: Easy-to-navigate UI for browsing menus and placing orders.
- **Payment Processing**: Secure and efficient payment gateway integration.
- **MySQL Database**: Robust database functionality for data storage and retrieval.
- **AWS Cloud Deployment**: Deployed on AWS for scalability and reliability.
- **CI/CD Pipelines**: Automated code commit, build, and deployment processes.

## Setup and Installation

### Prerequisites

- Apache/Nginx server
- PHP
- MySQL
- AWS Account (for deployment, if applicable)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/dipak-mohite/FoodyPicky.git
   cd FoodyPicky
   ```

2. **Move the project to your web server's root directory**:

   ```bash
   mv FoodyPicky /path/to/your/webserver/root
   ```

3. **Create a MySQL database and import the provided SQL file**:

   ```sql
   CREATE DATABASE foodypicky;
   USE foodypicky;
   SOURCE /path/to/your/webserver/root/FoodyPicky/database.sql;
   ```

4. **Configure the database connection**:

   Edit the `config.php` file in the project to set your MySQL database credentials.

5. **Launch the application**:

   Access the application through your web server (e.g., `http://localhost/FoodyPicky`).

## Deployment

FoodyPicky can be deployed on AWS using traditional web hosting methods. Ensure that your web server and database are correctly configured for production.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

**Dipak Mohite**

- [![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=LinkedIn)](https://www.linkedin.com/in/dipak-mohite/)
- [![GitHub](https://img.shields.io/badge/-GitHub-black?style=flat&logo=GitHub)](https://github.com/dipak-mohite)
- [![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat&logo=Instagram&logoColor=white)](https://www.instagram.com/dipakmohite01/)
- [![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=flat&logo=Twitter&logoColor=white)](https://x.com/dipakmohite01)
