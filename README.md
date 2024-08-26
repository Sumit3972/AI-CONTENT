Here's the updated `README.md` file with your credentials removed from the `.env` file:

```markdown
# Next.js Project

## Overview
This project is built using [Next.js](https://nextjs.org/), a React framework that enables several features, including server-side rendering and static site generation. The project also integrates with Clerk for authentication and Drizzle for database management.

## Features
- **Server-side Rendering**: Ensures fast load times and better SEO.
- **Authentication**: Implemented using Clerk.
- **Database Management**: Handled using Drizzle.
- **Payment Integration**: Razorpay is integrated for payment processing.

## Environment Variables
The project uses the following environment variables:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
CLERK_SECRET_KEY=<your_clerk_secret_key>

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_GOOGLE_GEMINI_API_KEY=<your_google_gemini_api_key>
NEXT_PUBLIC_DRIZZLE_DB_URL=<your_database_url>

RAZORPAY_KEY_ID=<your_razorpay_key_id>
RAZORPAY_SECRET_KEY=<your_razorpay_secret_key>

SUBSCRIPTION_PLAN_ID=<your_subscription_plan_id>
```

Ensure that these environment variables are set in your `.env.local` file before running the project.

## Getting Started

### Prerequisites
- Node.js (v14 or later)
- npm or yarn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-repo
   ```
3. Install the dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

### Running the Project

#### Development
To start the development server:
```bash
npm run dev
# or
yarn dev
```
The application will be available at `http://localhost:3000`.

#### Production
To build the project for production:
```bash
npm run build
# or
yarn build
```

To start the production server:
```bash
npm run start
# or
yarn start
```

#### Linting
To run the linter:
```bash
npm run lint
# or
yarn lint
```

### Database Management
To push changes to the database:
```bash
npm run db:push
# or
yarn db:push
```

To open the Drizzle Studio:
```bash
npm run db:studio
# or
yarn db:studio
```

## Contributing
If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [Next.js](https://nextjs.org/)
- [Clerk](https://clerk.dev/)
- [Drizzle](https://drizzle-orm.vercel.app/)
- [Razorpay](https://razorpay.com/)
```

This version removes all sensitive information, replacing it with placeholders. Make sure to store the actual credentials in your `.env.local` file.#   A I - C O N T E N T  
 