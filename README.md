# Recipe Website

Welcome to the Recipe Website! This README provides an overview of the project, including how to set it up, contribute, and use the features available on the site.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The Recipe Website is a platform where users can find, share, and save their favorite recipes. The website aims to provide a user-friendly interface for cooking enthusiasts to explore new dishes and share their culinary creations with the community.

## Features

- **Browse Recipes**: Explore a wide variety of recipes from different cuisines.
- **Search Functionality**: Easily find recipes by ingredients, cuisine, or recipe name.
- **User Accounts**: Sign up and log in to save favorite recipes and submit your own.
- **Recipe Submission**: Users can submit their own recipes, including ingredients, instructions, and photos.
- **Favorites**: Save favorite recipes for quick access later.
- **Ratings and Reviews**: Rate and review recipes to help others find the best dishes.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: Passport.js
- **Version Control**: Git, GitHub

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/dienebi-ombu/odin-recipes.git
    cd odin-recipe
    ```

2. **Install Dependencies**:
    ```bash
    npm install
    ```

3. **Set Up Environment Variables**:
    Create a `.env` file in the root directory and add the following variables:
    ```plaintext
    MONGODB_URI=your_mongodb_connection_string
    SESSION_SECRET=your_session_secret
    ```

4. **Start the Server**:
    ```bash
    npm start
    ```

The website should now be running on `http://localhost:3000`.

## Usage

- **Browse Recipes**: Visit the homepage to see a list of available recipes.
- **Search**: Use the search bar to find specific recipes.
- **User Accounts**: Sign up for a new account or log in with existing credentials.
- **Submit Recipes**: After logging in, use the "Submit Recipe" feature to add your own recipes.
- **Favorites**: Click the "Favorite" button on any recipe to save it to your favorites list.
- **Rate and Review**: Provide feedback on recipes by leaving ratings and reviews.

## Contributing

We welcome contributions to improve the Recipe Website! To contribute, follow these steps:

1. **Fork the Repository**:
    Click the "Fork" button on the GitHub repository page.

2. **Clone Your Fork**:
    ```bash
    git clone https://github.com/dienebi-ombu/odin-recipes.git
    cd odin-recipes
    ```

3. **Create a Branch**:
    ```bash
    git checkout -b feature/your-feature-name
    ```

4. **Make Your Changes**:
    Implement your feature or bug fix.

5. **Commit Your Changes**:
    ```bash
    git add .
    git commit -m "Add your commit message"
    ```

6. **Push to Your Fork**:
    ```bash
    git push origin feature/your-feature-name
    ```

7. **Submit a Pull Request**:
    Open a pull request on the original repository and provide a detailed description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or suggestions, feel free to open an issue on GitHub or contact the project maintainers:

- **Dienebi Ombu**: dienebi.ombu@gmail.com
- **GitHub**: [dienebi-ombu](https://github.com/dienebi-ombu)

---

Thank you for visiting the Recipe Website! We hope you enjoy exploring and sharing delicious recipes. Happy cooking!