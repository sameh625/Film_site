
# FilmSite

FilmSite is a web application for managing a personal film collection. Users can sign up, log in, add films, and view their collection in a dashboard.
We strongly focused on implementing **unit tests** and **integration tests** for every function in this project. All core logic and routes are covered by automated tests to ensure reliability and maintainability.

- **Unit Tests:** Test individual functions and modules in isolation.
- **Integration Tests:** Test the interaction between different modules and the overall workflow.


## Features

- User authentication (signup, login, logout)
- Add, view, and manage films
- Responsive UI with EJS templates
- MongoDB for data storage
- Session management

## Project Structure

```
.
├── app.js
├── controllers/
│   ├── filmController.js
│   └── userController.js
├── models/
│   ├── film.js
│   └── user.js
├── views/
│   ├── 404.ejs
│   ├── add-film.ejs
│   ├── index.ejs
│   ├── signup.ejs
│   └── welcome.ejs
├── partials/
│   ├── footer.ejs
│   ├── header.ejs
│   └── nav.ejs
├── public/
│   └── style.css
├── tests/
│   └── ...
├── package.json
```

## Getting Started

### Prerequisites

- Node.js
- MongoDB (Atlas or local)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/sameh625/filmsite.git
    cd filmsite
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Set up your MongoDB connection string in `app.js` (replace with your credentials if needed).

### Running the App

```sh
npm start
```

The app will run on [http://localhost:3000](http://localhost:3000).

### Running Tests

```sh
npm test
```

## Folder Descriptions

- `controllers/` - Route handlers for user and film logic
- `models/` - Mongoose schemas for User and Film
- `views/` - EJS templates for rendering pages
- `partials/` - Shared EJS partials (header, footer, nav)
- `public/` - Static assets (CSS)
- `tests/` - Automated tests
## Contributors

- [Sameh](https://github.com/sameh625)
- [Ameen](https://github.com/Ameensakr/)
