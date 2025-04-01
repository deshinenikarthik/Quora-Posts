# Quora-Posts - Simple Blog Application (Express.js)

This is a lightweight blogging application built using **Express.js** that allows users to create, edit, and delete posts, similar to Quora. The application features dynamic content rendering with **EJS** and maintains posts in-memory.

## 🔗 GitHub Repository
[Quora-Posts](https://github.com/deshinenikarthik/Quora-Posts.git)

## Features
- **View All Posts**: Displays a list of all posts (`/posts`).
- **Create New Posts**: Users can add new posts (`/posts/new`).
- **View Individual Posts**: View post details (`/posts/:id`).
- **Edit Posts**: Modify existing posts (`/posts/:id/edit`).
- **Delete Posts**: Remove posts from the list (`/posts/:id`).

## Technologies Used
- **Node.js** - Backend framework
- **Express.js** - Web framework
- **EJS** - View engine for rendering templates
- **UUID** - Generates unique post IDs
- **Method-Override** - Enables PUT & DELETE requests via forms
- **HTML & CSS** - Frontend styling

## Getting Started

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- npm (comes with Node.js)

### Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/deshinenikarthik/Quora-Posts.git
   cd Quora-Posts
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the application:
   ```sh
   node app.js
   ```
   or (for development using nodemon):
   ```sh
   npm start
   ```
4. Open your browser and navigate to `http://localhost:3000/posts`

## Usage
- Navigate to `/posts` to view all posts.
- Click **New Post** to create a post.
- Click on a post to view its details.
- Edit or delete posts using respective options.

## Future Enhancements
- Integrate **MongoDB** for persistent storage.
- Add **user authentication** to manage posts securely.
- Implement **comments & likes** features.

## Contributing
Contributions are welcome! Feel free to fork this repository, create a feature branch, and submit a pull request.

## License
This project is licensed under the MIT License.
