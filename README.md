# Krishi Seva

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fsih-blue.vercel.app)](https://sih-blue.vercel.app)

**Krishi Seva** is an innovative platform designed to empower farmers and agricultural professionals by providing a one-stop solution for managing agricultural activities, accessing valuable resources, and improving farming outcomes. It leverages modern technology to bridge the gap between farmers and essential services.

## Project Vision

The vision of **Krishi Seva** is to:
- Enhance agricultural productivity by providing timely information and guidance.
- Empower farmers with tools to make informed decisions.
- Foster a sustainable and prosperous farming ecosystem.

## Key Features

- **Sign Up & Create Your Profile**  
  Farmers and buyers can easily sign up and create a profile tailored to their needs.

- **Connect & Negotiate**  
  Use our platform to discover potential partners and establish secure contracts.

- **Deliver & Get Paid**  
  Farmers deliver the produce as per the contract and receive timely payments.
  
- **Multi-language Support**  
  The platform is designed to cater to farmers across diverse regions by supporting multiple languages.

## Benefits to Farmers

1. **Increased Productivity:** Access to scientific data and expert guidance improves crop yields.
2. **Cost Efficiency:** Informed decisions help reduce unnecessary expenses on seeds, fertilizers, and pesticides.
3. **Contract-Farming:** Contract farming provides farmers with a pre-determined buyer for their produce, reducing the risks of market fluctuations and eliminating the uncertainty of finding buyers.
4. **Ease of Access:** Mobile-friendly design ensures farmers can access resources anytime, anywhere.

## Tech Stack

The **Krishi Seva** platform is built using the following technologies:

- **Frontend:** React.js (modern, responsive UI)
- **Backend:** Node.js with Express (robust API handling)
- **Database:** Firebase
- **Styling:** Tailwind CSS (for elegant, responsive designs)
- **Hosting:** Vercel (fast, secure, and reliable deployment)

## Installation and Development

To set up this project locally, follow these steps:

### Prerequisites

Ensure you have the following installed:

- Node.js (v16 or later)
- npm or yarn package manager

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/krishi-seva.git
   cd krishi-seva



## Getting Started

1. Install all dependencies
```bash
npm install
```

2. Create a `.env.local` file in the server directory and add in the firebase config data to connect to firebase : 
```
FIREBASE_API_KEY=xxx
FIREBASE_AUTH_DOMAIN=xxx
FIREBASE_PROJECT_ID=xxx
FIREBASE_STORAGE_BUCKET=xxx
FIREBASE_MESSAGING_SENDER_ID=xxx
FIREBASE_APP_ID=xxx

```
- Client-Side (if needed): If any of these variables are also needed on the client side, you'll need to duplicate them with the VITE_ prefix and place them in the .env file:
```
VITE_FIREBASE_API_KEY=xxx
VITE_FIREBASE_AUTH_DOMAIN=xxx
VITE_FIREBASE_PROJECT_ID=xxx
VITE_FIREBASE_STORAGE_BUCKET=xxx
VITE_FIREBASE_MESSAGING_SENDER_ID=xxx
VITE_FIREBASE_APP_ID=xxx
```
This way, your server-side environment variables remain secure, while the client-side variables are correctly exposed using Vite's import.meta.env method if needed.
In Server-side make use of `dotenv` package and make sure to import config.js and use `process.env.FIREBASE_*` when needed.

Contact any of the maintainers for the contents of the `.env.local` file

Then, run in the client folder terminal:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start contributing by creating your own branch and raising a PR ;)
