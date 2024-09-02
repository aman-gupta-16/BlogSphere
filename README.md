

# BlogSphere

**BlogSphere** is a full-stack web application designed for creating, managing, and sharing blog posts. It features user authentication, a rich text editor for writing posts, and a user-friendly interface to explore blogs.

## Features

- **User Authentication:** Register, log in, and manage your account.
- **Create and Edit Posts:** Use a rich text editor to write and format your blog posts.
- **Responsive Design:** Works seamlessly across different devices.
- **Post Management:** Edit or delete your posts.
- **Explore Blogs:** Browse blogs from various users.

## Installation

To set up this project locally, follow these steps:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/aman-gupta-16/BlogSphere.git
    cd BlogSphere
    ```

2. **Install Dependencies:**

    Ensure you have Node.js installed, then run:

    ```bash
    npm install
    ```

3. **Set Up the Database:**

    - Create a `.env` file in the root directory and add the following environment variables:

      ```bash
      DB_URI=<your_mongodb_uri>
      SECRET_KEY=<your_secret_key>
      ```

    - Replace `<your_mongodb_uri>` with your MongoDB connection string and `<your_secret_key>` with a secure key for session management.

4. **Run the Application:**

    Start the application using:

    ```bash
    npm start
    ```

    The application will be available at `http://localhost:3000`.

## Usage

1. **Register/Login:**
   - Create an account or log in with your existing credentials.

2. **Create a Post:**
   - Navigate to the "Create Post" section and use the editor to write your blog.
   - Add a title, content, and format it as needed.

3. **Manage Posts:**
   - View, edit, or delete your posts from the dashboard.

4. **Explore Blogs:**
   - Browse blogs posted by other users and engage with the content.

## Project Structure

```
BlogSphere/
│
├── views/              # EJS templates for rendering the frontend
│   ├── partials/       # Reusable partial templates
│   ├── home.ejs        # Homepage template
│   ├── posts/          # Templates for blog post pages
│   └── ...             # Other views
│
├── public/             # Static files (CSS, JS, images)
│   ├── css/            # Stylesheets
│   ├── js/             # Client-side JavaScript
│   └── ...             # Other assets
│
├── routes/             # Express route handlers
│   ├── index.js        # Main routes
│   ├── posts.js        # Routes for blog posts
│   └── users.js        # Routes for user authentication
│
├── models/             # Mongoose models
│   ├── Post.js         # Blog post schema
│   └── User.js         # User schema
│
├── config/             # Configuration files
│   └── db.js           # Database connection setup
│
├── .env                # Environment variables
├── app.js              # Main application entry point
├── package.json        # Project dependencies and scripts
└── README.md           # Project documentation
```

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch with your feature or bug fix.
3. Commit your changes and push them to your branch.
4. Open a pull request with a description of your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any questions or feedback, feel free to reach out:

- **Aman Gupta**

---

This README provides an overview of the BlogSphere project, guiding users from installation to contribution. Customize it further as needed!
