🚀 Project Title & Tagline
============================
**MRK_GPT** 🤖

*Clone Of the ChatGPT
CHATGPT-Clone is a simple AI chat application that replicates the core experience of interacting with ChatGPT. It allows users to send messages, receive intelligent responses, and explore how modern conversational AI works behind the scenes. This project is built to help beginners understand API integration, frontend–backend communication, and real-time chat functionality. It’s lightweight, easy to customize, and perfect for learning or extending into a more advanced AI-powered assistant.*

## Live Demo  
You can access the live version of this project: [Here!!](https://mrk-gpt.vercel.app)


✨ Features
-----------
Here are some of the key features of the Assistant UI Starter:
* **AI-powered text streaming**: Stream text data using the `streamText` function from the `ai` library
* **Responsive design**: Use the `twMerge` function from `tailwind-merge` to create responsive, mobile-friendly UI components
* **Customizable theme**: Define your own theme using CSS variables and the `@theme` directive
* **Next.js support**: Build scalable, performant applications using Next.js
* **TypeScript support**: Use TypeScript to write type-safe, maintainable code
* **Pre-configured scripts**: Get started with development quickly using pre-configured scripts for development, building, and deployment
* **Mobile support**: Use the `useIsMobile` hook to detect mobile devices and adapt your UI accordingly
* **Google AI SDK integration**: Integrate with the Google AI SDK using the `@ai-sdk/google` library

🧰 Tech Stack Table
-------------------
| Category | Technology |
| --- | --- |
| Frontend | React, Next.js, TypeScript |
| Backend | Node.js (optional) |
| Tools | Webpack, Turbopack, Tailwind CSS, clsx |

📁 Project Structure
---------------------
The project is organized into the following folders:
* `components`: Reusable UI components
* `pages`: Next.js pages
* `public`: Static assets
* `styles`: Global CSS styles
* `utils`: Utility functions
* `node_modules`: Installed dependencies

Here's a brief explanation of each folder:
* `components`: This folder contains reusable UI components, such as buttons, inputs, and cards. These components can be used throughout the application to maintain a consistent look and feel.
* `pages`: This folder contains Next.js pages, which are used to define the application's routes and layout.
* `public`: This folder contains static assets, such as images, fonts, and other files that need to be served directly by the web server.
* `styles`: This folder contains global CSS styles, including the `globals.css` file, which defines the application's theme and layout.
* `utils`: This folder contains utility functions, such as the `cn` function, which is used to merge class names.
* `node_modules`: This folder contains installed dependencies, such as React, Next.js, and TypeScript.

⚙️ How to Run
--------------
To get started with the project, follow these steps:
1. Clone the repository using `git clone`
2. Install dependencies using `npm install` or `yarn install`
3. Start the development server using `npm run dev` or `yarn dev`
4. Build the application using `npm run build` or `yarn build`
5. Deploy the application using `npm run start` or `yarn start`

Make sure you have Node.js and npm installed on your machine before running the project.

🧪 Testing Instructions
-----------------------
To test the project, follow these steps:
1. Run `npm run test` or `yarn test` to run the unit tests
2. Run `npm run test:e2e` or `yarn test:e2e` to run the end-to-end tests
3. Use a testing library like Jest or Mocha to write and run tests

Note: These screenshots are placeholders and will be replaced with actual screenshots of the application.

📦 API Reference
----------------
The application uses the following APIs:
* **Google AI SDK**: The application uses the Google AI SDK to integrate with Google's AI services.
* **Next.js API**: The application uses the Next.js API to handle requests and responses.

Here is an example of how to use the Google AI SDK API:
```typescript
import { google } from "@ai-sdk/google";

const api = google.ai();
const response = await api.streamText({
  // API options here
});
```

👤 Author
----------
The Assistant UI Starter was created by [Yours Truly](https://github.com/19e11).

📝 License
----------
The Assistant UI Starter is licensed under the [MIT License](https://opensource.org/licenses/MIT).
