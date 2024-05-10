---

# Friends App

Welcome to the Friends App repository! This project is a web application designed to help users manage their friendships effectively. It provides a platform where users can create, update, and delete their friends' profiles, send and accept friend requests, and explore their network of friends.

## Features

- **User Authentication**: The application employs a robust user authentication system using Devise gem, ensuring secure access to user accounts and data.
- **CRUD Operations**: Users can perform CRUD (Create, Read, Update, Delete) operations on friend records, enabling them to maintain an up-to-date list of friends.
- **Search Functionality**: The app offers a comprehensive search feature, allowing users to find friends by various attributes such as name, location, interests, etc.
- **Friend Requests**: Users can send and accept friend requests, facilitating the establishment of new connections within the platform.
- **User Profiles**: Each user has a dedicated profile page where they can view and edit their personal information, providing a customizable experience.

## Technologies Used

- **Ruby on Rails**: The backend of the application is powered by Ruby on Rails, a powerful web development framework known for its convention over configuration principle and rapid development capabilities.
- **JavaScript with Node.js**: JavaScript, along with Node.js, is utilized for frontend scripting, enabling dynamic interactions and seamless user experiences.
- **Yarn**: Yarn serves as the package manager for managing frontend dependencies efficiently, ensuring consistent and reliable frontend development.
- **SQLite3**: For development purposes, the application uses SQLite3, a lightweight SQL database engine, to store and manage data locally.
- **Bootstrap**: Bootstrap, a popular frontend framework, is integrated into the project to facilitate responsive and mobile-first web development, ensuring compatibility across various devices and screen sizes.

## Installation

1. **Clone the Repository**: Begin by cloning the repository to your local machine using the following command:

   ```
   git clone https://github.com/your-username/friends-app.git
   ```

2. **Navigate to Project Directory**: Move into the project directory using the following command:

   ```
   cd friends-app
   ```

3. **Install Ruby Dependencies**: Install Ruby dependencies required for the project using Bundler:

   ```
   bundle install
   ```

4. **Install JavaScript Dependencies**: Install JavaScript dependencies using Yarn:

   ```
   yarn install
   ```

5. **Set up the Database**: Create and migrate the database using the following commands:

   ```
   rails db:create
   rails db:migrate
   ```

6. **Start the Server**: Launch the Rails server to run the application locally:

   ```
   rails server
   ```

7. **Access the Application**: Once the server is running, access the application in your web browser at `http://localhost:3000`.

## Contributing

Contributions to the Friends App project are welcome! If you have any suggestions, improvements, or feature requests, feel free to open an issue or create a pull request. Your contributions help enhance the project and make it more valuable for the community.

## References & Documentation

- [Ruby on Rails Guides](https://guides.rubyonrails.org/): Comprehensive documentation for Ruby on Rails, offering guidance on various aspects of web development using Rails.
- [Devise Gem Documentation](https://github.com/heartcombo/devise): Documentation for Devise, a flexible authentication solution for Rails applications, providing a robust user authentication system.
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.1/getting-started/introduction/): Official documentation for Bootstrap, offering detailed information and examples for utilizing the Bootstrap framework in web development.
- [Node.js Documentation](https://nodejs.org/en/docs/): Extensive documentation for Node.js, covering topics ranging from installation and basic usage to advanced features and modules.
- [Yarn Documentation](https://yarnpkg.com/getting-started): Official documentation for Yarn, providing guidance on installation, usage, and configuration of the Yarn package manager for JavaScript projects.

---
