AI UI Library SaaS 

An AI-powered React UI Library built using the MERN Stack. This project allows developers to generate React UI components using AI prompts and provides a reusable component library that can be distributed through NPM.

Features

1.AI-powered UI component generation
2. React frontend with Vite
3. Node.js and Express backend
4. MongoDB database integration
5. User authentication system
6. Razorpay payment integration
7.Custom UI component library
8.Deployable SaaS architecture

Tech Stack

Frontend

- React.js
- Vite
- Axios
- Tailwind CSS

Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

Integrations

- OpenRouter API
- Razorpay
- GitHub
- NPM

Project Structure

ai-ui-saas/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── server.js
│   └── package.json
│
└── README.md

Installation

Clone Repository

git clone https://github.com/your-username/ai-ui-saas.git
cd ai-ui-saas

Backend Setup

cd server
npm install
npm start

Frontend Setup

cd client
npm install
npm run dev

Environment Variables

Create a ".env" file in the server folder:

MONGO_URL=your_mongodb_url
JWT_SECRET=your_secret_key
OPENROUTER_KEY=your_api_key
RAZORPAY_KEY=your_key
RAZORPAY_SECRET=your_secret

Deployment

Frontend

Deploy on Vercel.

Backend

Deploy on Render.

Database

Use MongoDB Atlas.

Future Enhancements

- Google Authentication
- Subscription Plans
- Component Marketplace
- Live Component Preview
- Dark Mode Support
- AI Chat Assistant


License

MIT License
