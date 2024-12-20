# MyContacts Backend

A RESTful API for managing contact information.

## Features
- Create, read, update, and delete (CRUD) contacts.
- Search and filter contacts by attributes.
- Secure API with authentication and validation.

## Technologies Used
- Backend: Node.js, Express
- Database: MongoDB
- Authentication: JWT (JSON Web Tokens)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mmoladaa/mycontacts-backend.git
   ```
2. Navigate to the project directory:
   ```bash
   cd mycontacts-backend
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## API Endpoints
- `GET /contacts` - Fetch all contacts.
- `POST /contacts` - Add a new contact.
- `PUT /contacts/:id` - Update a contact.
- `DELETE /contacts/:id` - Delete a contact.
