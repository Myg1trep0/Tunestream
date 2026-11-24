# Backend API Service

Node.js and Express REST API backend for managing media assets, authentication, and playlist endpoints.

## Setup & Running

```bash
npm install
npm run server
```

## Environment Configuration
See `.env.example` for the required configuration keys:
- `PORT`: Service port (default 4000)
- `MONGODB_URI`: MongoDB connection string
- `CLOUDINARY_NAME`, `CLOUDINARY_API_KEY`, `CLOUDINARY_SECRET_KEY`: Media CDN keys
- `JWT_SECRET`: Signing key for user session tokens
