## NestJS, Clean Architecture, and TypeScript

**Advanced Node.js Project with Clean Architecture, NestJS, and TypeScript**

### Index

* **About the Project**
* **Project Architecture**
* **Prerequisites**
* **Installation**
* **Configuration**
* **Available Commands**
* **Folder Structure**
* **Contributing**
* **License**

### About the Project
This project is a modular and scalable API, developed with NestJS, following Clean Architecture principles and implemented with TypeScript.

### Project Architecture
The project follows Clean Architecture principles, ensuring separation of concerns and ease of maintenance. The structure is divided into layers:
* **Domain:** Contains entities, business rules, and use cases.
* **Application:** Manages use cases and orchestration between layers.
* **Infrastructure:** Technical implementation, including database and integration with external services.
* **Presentation:** Routing and input/output manipulation.

### Prerequisites
Make sure you have the following programs installed on your system:

* Node.js (version X or higher)
* npm or yarn
* Docker (optional, for container execution)

### Installation
1. Clone the repository:
   ```
   git clone [https://github.com/your-user/your-repository.git](https://github.com/your-user/your-repository.git)
   ```
2. Navigate to the project directory:
   ```
   cd your-repository
   ```
3. Install dependencies:
   ```
   npm install # or yarn install
   ```
4. Configure environment variables (see Configuration).

### Configuration
Create a `.env` file in the project root with the following variables (example):
```
DATABASE_URL=postgresql://user:password@localhost:5432/database
JWT_SECRET=your_secret_key
PORT=3000
```

### Available Commands
* **Run the project in development:**
   ```
   npm run start:dev
   ```
* **Build the project for production:**
   ```
   npm run build
   ```
* **Run tests:**
   ```
   npm test
   ```
* **Run lint:**
   ```
   npm run lint
   ```

### Folder Structure
```
src/
├── domain/              # Entities and business rules
├── application/         # Use cases and orchestration
├── infrastructure/      # Database, external services, and technical configurations
├── presentation/        # Routes, controllers, and input/output manipulation
└── main.ts              # Main file for application initialization
```

### Contributing
If you want to contribute to this project:
1. Fork the repository.
2. Create a branch for your feature: `git checkout -b my-new-feature`.
3. Commit your changes: `git commit -m 'Adds new feature'`.
4. Push to the main branch: `git push origin my-new-feature`.
5. Open a Pull Request.
