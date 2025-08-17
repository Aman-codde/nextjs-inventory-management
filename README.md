# Build a Fullstack Inventory Management Dashboard

A fullstack Inventory Management application built with Next.js (frontend) and Node.js/Express (backend) for managing products and stock levels efficiently.

## Tech Stack

- **Next JS**
- **Tailwind**
- **Redux Toolkit**
- **Redux Toolkit Query**
- **Material UI Data Grid**
- **Node.js**
- **Prisma**
- **AWS EC2**
- **AWS RDS**
- **AWS API Gateway**
- **AWS Amplify**
- **AWS S3**

## Project Structure

```
inventory-management/
│
├── client/           # Next.js frontend application
├── server/           # Node.js backend with Express and Prisma
└── README.md         # Project documentation
```

## Installation

### Clone the repository

```bash
git clone https://github.com/Aman-codde/nextjs-inventory-management.git
cd nextjs-inventory-management
```

### Setup Backend

```bash
cd server
npm install
```

- Create a `.env` file with your database credentials.
- Run the server:

```bash
npm run dev
```

### Setup Frontend

```bash
cd ../client
npm install
npm run dev
```

- Frontend will run on `http://localhost:3000`

## Usage

- Open frontend and use the dashboard to manage products and stock.
- Backend APIs handle all CRUD operations.

## API Endpoints (Server)

| Method | Endpoint           | Description       |
| ------ | ------------------ | ----------------- |
| GET    | /api/products      | Get all products  |
| POST   | /api/products      | Add a new product |
| PUT    | /api/products/\:id | Update a product  |
| DELETE | /api/products/\:id | Delete a product  |

## Contributing

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`.
3. Commit changes: `git commit -m "Add feature"`.
4. Push to branch: `git push origin feature/your-feature`.
5. Create a pull request.

## License

This project is licensed under the MIT License.

