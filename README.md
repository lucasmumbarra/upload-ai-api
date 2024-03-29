# Upload AI API

## Description

This project is an API for handling file uploads and integrating with AI services. It utilizes Fastify as the web framework, TypeScript for type-checking, and Prisma for database operations.

## Installation

Before running the project, make sure you have Node.js and npm installed on your machine.

1. Clone the repository:

```bash
git clone <repository-url>
cd upload-ai-api
```

2. Install dependencies:

```bash
npm install
```

3. Create a .env file in the root directory and add the necessary environment variables, such as API keys and database connection details.

## Running the Project

To run the project in development mode, execute the following command:

```bash
npm run dev
```

This will start the TypeScript compiler in watch mode and launch the server using tsx.

## Dependencies

- **@fastify/cors:** Cross-Origin Resource Sharing (CORS) support for Fastify.
- **@fastify/multipart:** Handling multipart/form-data for file uploads in Fastify.
- **@prisma/client:** Prisma client for interacting with the database.
- **ai:** AI library (version 2.2.33) - Provide the required API keys and configurations.
- **fastify:** Fast and low overhead web framework for Node.js.
- **openai:** OpenAI library for integration with OpenAI services.
- **zod:** TypeScript-first schema declaration and validation.

## Development Dependencies

- **@types/node:** TypeScript type definitions for Node.js.
- **dotenv:** Module for loading environment variables from a .env file.
- **prisma:** Prisma CLI and type generation for database operations.
- **tsx:** TypeScript execution environment for running TypeScript files.
- **typescript:** TypeScript language and compiler (version 5.3.3).

## License

This project is licensed under the ISC License.

Feel free to explore and enhance the functionalities of the Upload AI API!
