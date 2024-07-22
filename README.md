
# CodeResolve

This is a StackOverflow clone built with Next.js and Appwrite. It uses the Appwrite Node.js SDK to interact with the Appwrite API. The UI is built using Tailwind CSS and the magicui library, and the database is stored in Appwrite.

## Features

- User authentication with email and password
- Questions and answers
- Voting system
- Comments
- Markdown support
- Search functionality
- Themes

## Getting Started

### Prerequisites

- Node.js (version 16.14.0 or higher)
- Appwrite (version 1.0.0 or higher)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Ashwinhegde19/coderesolve.git
   cd coderesolve
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up Appwrite:**

   - Follow the [Appwrite installation guide](https://appwrite.io/docs/installation) to set up your Appwrite server.
   - Create a new project in Appwrite.
   - Create the necessary collections (e.g., users, questions, answers, comments, votes).
   - Set up environment variables for Appwrite in a `.env` file:

     ```env
     NEXT_PUBLIC_APPWRITE_ENDPOINT=https://[YOUR APPWRITE ENDPOINT]
     NEXT_PUBLIC_APPWRITE_PROJECT_ID=[YOUR PROJECT ID]
     ```

4. **Run the development server:**

   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Building for Production

To create an optimized production build:

```bash
npm run build
npm start
```

### Learn More

To learn more about Next.js and Appwrite, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Appwrite Documentation](https://appwrite.io/docs) - learn about Appwrite features and API.

## Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
```

