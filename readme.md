# Browser Extensions Manager Backend

A backend server for managing browser extensions, providing APIs for extension data, user management, and integration with browser clients.

## Features

- RESTful API for extension management
- Database integration
- Logging and error handling

## Tech Stack

- Node.js
- Express.js
- MongoDB (or your preferred database)

## Getting Started

### Prerequisites

- Node.js (v20+)
- npm or yarn
- MongoDB instance

### Installation

```bash
git clone https://github.com/yourusername/browser-extensions-manager-backend.git
cd browser-extensions-manager-backend
npm install
```

### Configuration

Create a `.env` file in the root directory:

```js
PORT=3000
MONGODB_URI=mongodb://localhost:27017/extensions-manager
```

### Running the Server

```bash
npm start
```

## API Endpoints

| Method | Endpoint           | Description                |
|--------|--------------------|----------------------------|
| GET    | /api/extensions    | List all extensions        |
| POST   | /api/extensions    | Add a new extension        |
| PUT    | /api/extensions/:id| Update an extension        |
| DELETE | /api/extensions/:id| Delete an extension        |
| POST   | /api/auth/login    | User login                 |
| POST   | /api/auth/register | User registration          |

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/feature-name`)
3. Commit your changes
4. Push to the branch
5. Open a pull request

## License

MIT
