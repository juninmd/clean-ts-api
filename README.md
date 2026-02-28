```markdown
# clean-ts-api

**Description:** API em NodeJs usando Typescript, TDD, Clean Architecture, Design Patterns e SOLID principles.

---

**Installation:**

1.  Clone the repository: `git clone https://github.com/your-username/clean-ts-api`
2.  Navigate to the project directory: `cd clean-ts-api`
3.  Install dependencies: `npm install`
4.  Configure Docker: `docker-compose up` (This will build and run the API).

---

**Usage:**

*   **Project Structure:** The project is organized as follows:
    *   `src/`: Contains the core API logic.
        *   `api.js`:  Main API endpoint.
        *   `models/`:  Database models (e.g., User, Product).
        *   `services/`:  Business logic services (e.g., OrderService, ProductService).
        *   `utils/`:  Helper functions and utility modules.
    *   `tsconfig-build.json`: TypeScript configuration for building the project.
    *   `tsconfig.json`: TypeScript configuration for the project.
    *   `jest-integration-config.js`: Jest configuration for testing.
    *   `jest-mongodb-config.js`: MongoDB configuration for testing.
    *   `jest-unit-config.js`: Jest unit test configuration.
    *   `jest.config.js`: Jest configuration.
    *   `package.json`: Project metadata, dependencies, and scripts.
    *   `public/`: Static assets (e.g., CSS, images).
    *   `README.md`: Project documentation.
    *   `LICENSE`: License information.
    *   `requirements.txt`: Node.js dependencies.
    *   `docker-compose.yml`: Docker Compose configuration for the API.
    *   `package-lock.json`: Docker image locking.
    *   `package.json`: Application metadata, including environment variables.
    *   `src/index.js`: Entry point for the API.


*   **Testing:**  Run `npm test` to execute the tests.
*   **Development:**  Use `npm run build` to build the API for deployment.
*   **Deployment:** Deploy using `docker-compose up -d` after configuring `docker-compose.yml`.
```