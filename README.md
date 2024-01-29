# Hotel Reservation Web API (ASP.NET 7.0)

Welcome to the Hotel Reservation Web API built with ASP.NET 7.0 and MongoDB. This API provides a robust set of functionalities for managing hotel reservations, including user authentication, authorization, email verification, change password, reservation creation, cancellation, and more.

## Features

### User Authentication and Authorization

- **Registration:** Users can securely register by providing necessary details, and their passwords are securely hashed before storage.
- **Login:** Registered users can log in to access secured endpoints.
- **Email Verification:** An email verification system ensures the authenticity of user emails. After registration, users receive a verification link via email.
- **Change Password:** Users can securely change their passwords by providing the current and new passwords.
- **Authentication and Authorization:** Access to various API endpoints is restricted based on user roles, ensuring secure operations.

### Reservation Management

- **Create Reservation:** Users can create reservations by providing details such as name, check-in, check-out dates, and room type.
- **Cancel Reservation:** Reserved rooms can be canceled, freeing up availability for other guests.

### Email Notification

- **Email Notification:** Users receive email notifications for important events, such as registration and reservation creation.

## How to Use

1. **Clone the Repository:** Begin by cloning the project repository to your local machine.

    ```bash
    git clone https://github.com/yourusername/hotel-reservation-api.git
    ```

2. **Setup MongoDB:** Ensure that you have MongoDB installed and configured. Update the `appsettings.json` file with your MongoDB connection details.

3. **Configure Email Settings:** Update the `appsettings.json` file with your SMTP server details for email notification functionality.

4. **Build and Run the Application:** Open the solution in your preferred IDE (Visual Studio, VS Code) and build/run the project.

5. **API Documentation:** Explore the API documentation to understand available endpoints and how to interact with them.

## API Documentation

API documentation, including endpoint details and examples, is available at [https://yourwebsite.com/api/docs](https://yourwebsite.com/api/docs). This Swagger-based documentation provides an interactive and user-friendly interface.

## Contributions

Contributions to enhance and refine the Hotel Reservation Web API are welcome. Feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License.
