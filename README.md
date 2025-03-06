# project-blog-api

## Goal

Build a blog API that covers all HTTP requests (except PUT) to display information in the front end by connecting to our back end.
CRUD methods: CREATE/READ/UPDATE/DELETE.

## API Endpoints and HTTP Methods

### Challenge 1: GET All Posts

- **HTTP Method**: GET
- **Endpoint**: `/posts`
- **Description**: Retrieves all blog posts

### Challenge 2: GET a Specific Post

- **HTTP Method**: GET
- **Endpoint**: `/posts/:id`
- **Description**: Retrieves a single blog post by its ID

### Challenge 3: POST a New Post

- **HTTP Method**: POST
- **Endpoint**: `/posts`
- **Description**: Creates a new blog post

### Challenge 4: PATCH a Post

- **HTTP Method**: PATCH
- **Endpoint**: `/posts/:id`
- **Description**: Updates specific fields of an existing blog post

### Challenge 5: DELETE a Post

- **HTTP Method**: DELETE
- **Endpoint**: `/posts/:id`
- **Description**: Deletes a blog post by its ID
