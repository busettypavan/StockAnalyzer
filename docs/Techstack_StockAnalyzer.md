## Detailed Technology Stack by Layer

| Layer                       | Recommended Technology                   | Purpose                                                                              |
| --------------------------- | ---------------------------------------- | ------------------------------------------------------------------------------------ |
| Frontend framework          | React.js + TypeScript                    | Build the stock dashboard and reusable components.                                   |
| Frontend build tool         | Vite                                     | Enable fast local development and production builds.                                 |
| UI styling                  | Tailwind CSS or CSS Modules              | Create a responsive dashboard and style components.                                  |
| API communication           | Fetch API or Axios                       | Call Python backend endpoints.                                                       |
| Authentication UI           | Firebase Web SDK                         | Implement login, logout, registration, and token retrieval.                          |
| Backend framework           | Python 3.12+ with FastAPI                | Build REST APIs and handle requests.                                                 |
| API validation              | Pydantic                                 | Validate incoming requests and API responses.                                        |
| Authentication verification | Firebase Admin SDK                       | Verify Firebase ID tokens on the backend.                                            |
| Primary database            | Cloud Firestore                          | Store users' positions, stock reference data, and cached price history.              |
| Future database             | PostgreSQL                               | Provide relational persistence for advanced portfolio and analytical features.       |
| Database abstraction        | Repository Pattern                       | Separate business logic from Firestore and PostgreSQL implementations.               |
| Authentication abstraction  | Provider Interface                       | Support Firebase Authentication initially and allow Supabase Auth integration later. |
| Market data                 | `yfinance`                             | Retrieve daily historical prices for NSE-listed stocks.                              |
| Data processing             | pandas, NumPy                            | Process historical prices and perform calculations.                                  |
| Technical indicators        | `pandas-ta`                           | Implement the 10 approved technical indicators.                                      |
| Charting                    | React financial chart library            | Display candlestick and price charts, overlays, volume, and signal markers.          |
| Testing                     | Pytest, Vitest, React Testing Library    | Run automated backend and frontend tests.                                            |
| Code quality                | Ruff, ESLint, Prettier, Mypy             | Perform linting, formatting, and type checking.                                      |
| Version control             |  GitHub                                 | Manage source code, pull requests, and issues.                                       |
| Configuration               | Environment variables + `.env.example` | Manage local configuration without committing secrets.                               |
|                             |                                          |                                                                                      |
