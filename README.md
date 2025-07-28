# SampleApp - Ruby on Rails Application

A sample Ruby on Rails application demonstrating user authentication, microposts, and social features.

## Features

- **User Authentication**: Sign up, login, logout with secure password handling
- **User Profiles**: View and edit user profiles with avatar support
- **Microposts**: Create, edit, and delete short posts
- **Following System**: Follow/unfollow other users
- **Feed**: Personalized feed showing posts from followed users
- **Account Activation**: Email-based account activation
- **Password Reset**: Secure password reset functionality
- **Admin Users**: Administrative capabilities for managing users

## Technology Stack

- **Ruby on Rails** 7.x
- **Ruby** 3.x
- **SQLite** (development)
- **Bootstrap** for styling
- **Stimulus** for JavaScript functionality
- **Active Storage** for file uploads

## Getting Started

### Prerequisites

- Ruby 3.x or higher
- Rails 7.x
- SQLite3
- Node.js and Yarn (for asset compilation)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mirkodev93/SampleApp_Ruby.git
   cd SampleApp_Ruby
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Set up the database**
   ```bash
   rails db:migrate
   rails db:seed
   ```

4. **Start the server**
   ```bash
   rails server
   ```

5. **Visit the application**
   Open your browser and go to `http://localhost:3000`

## Usage

### Creating an Account
1. Visit the signup page
2. Fill in your details
3. Check your email for activation link
4. Click the activation link to activate your account

### Using the Application
- **Home**: View your personalized feed
- **Profile**: Edit your profile and view your posts
- **Users**: Browse and follow other users
- **Microposts**: Create and manage your posts

## Project Structure

```
app/
├── controllers/     # Application controllers
├── models/         # ActiveRecord models
├── views/          # ERB templates
├── helpers/        # View helpers
├── mailers/        # Email functionality
├── javascript/     # Stimulus controllers
└── assets/         # Stylesheets and images
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

**Mirko Milicevic** - [GitHub Profile](https://github.com/mirkodev93)

---

Built with ❤️ using Ruby on Rails
