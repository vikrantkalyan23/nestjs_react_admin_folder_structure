# nestjs_react_admin_folder_structure

A well-structured folder hierarchy helps maintain scalability, modularity, and ease of understanding in your NestJS (backend) and ReactJS (frontend) admin panel project. Here's a recommended folder structure for both


# Integration Tips

    API Endpoints:

        Keep the endpoints consistent between the backend and frontend.

        Use environment variables for API URLs (.env).

    Authentication:

        Use JWT for managing sessions.

        Store tokens in httpOnly cookies for better security or localStorage for simplicity.

    Environment Variables:

        Backend: Use @nestjs/config to load .env.

        Frontend: Use dotenv for managing .env variables.