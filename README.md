# Movie Watchlists API

This project is a Proof of Concept (POC) for a Movie Watchlists API built using Ruby on Rails 8. It provides endpoints for managing users, movies, and watchlists.

## Features

- **User Management**: Create and manage user accounts.
- **Movie Management**: Add, update, and delete movies in the database.
- **Watchlist Management**: Allow users to create and manage their personal movie watchlists.

## Requirements

- **Ruby Version**: 3.3.5
- **Rails Version**: 8.0.1
- **System Dependencies**: PostgreSQL

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/csalasb86/movie-watchlists-api.git
   cd movie-watchlists-api
   ```

2. **Install Dependencies**:

   ```bash
   bundle install
   ```

3. **Database Setup**:

   ```bash
   rails db:create
   rails db:migrate
   ```

4. **Run the Application**:

   ```bash
   rails server
   ```

   Access the application at `http://localhost:3000`.

## Configuration

Provide any necessary configuration details here.

## Testing

To run the test suite:

```bash
rails test
```

## Deployment

Instructions for deploying the application.

## Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are welcome.

## License

Specify the license under which the project is distributed.

## Contact

For any inquiries or issues, please open an issue on the repository or contact the maintainer.