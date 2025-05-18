# Tech-Discussions

Here’s a **summary** for your project README:

This is a simple web application that allows users to sign up, log in, create posts, comment, edit, and delete their own posts. It also features RESTful APIs and integrates email, SMS, and in-app notifications to enhance user interaction. It features user authentication, post creation, editing, and deletion functionalities. Comments can be added to each post. The project uses RESTful APIs to handle CRUD operations for posts and comments.

Additional features include:

* ✉️ **Email & SMS Notifications**: Users are notified via email and SMS when key actions occur (like new likes, comments, or replies).
* 📝 **Edit & Delete**: Authenticated users can edit or delete their own posts via dedicated routes.
* 📬 **Notifications Endpoint**: In-app and external notifications are triggered through a `POST /notifications` endpoint.
* 🔄 **RESTful API Routes**:

  * `GET /posts` – Fetch all posts
  * `POST /posts` – Create a new post
  * `GET /posts/:id/edit` – Render post edit page
  * `PATCH /posts/:id` – Update a post
  * `DELETE /posts/:id` – Delete a post
  * `POST /posts/:id/comments` – Add comment to a post
  * `GET /users/:id/notifications` – Fetch user notifications

This project uses **Node.js**, **Express**, **EJS**, and **method-override**, and integrates frontend interactivity with clean blue-and-white themed CSS styling.

---

Let me know if you want a detailed README version with installation and usage instructions!

