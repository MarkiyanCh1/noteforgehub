# 📝 NoteForgeHub

[![NoteForgeHub](/public/logo.png)](https://github.com/MarkiyanCh1/noteforgehub)

NoteForgeHub is a single space where you can think, write, and plan. Capture thoughts, manage projects, or even run an entire company — and do it exactly the way you want. This project is a fun experiment to create a functional clone of Notion, a popular note-taking and productivity application.

## 🌐 Live Website

- The application is live and hosted on Vercel. You can access it [here](https://noteforgehub.vercel.app/).

## 📸 Screenshot

- Marketing Page
  ![Marketing Page](/public/marketing-screenshot.png)
- Main Page
  ![Main Page](/public/notes-screenshot.png)

## 🌟 Features

- Marketing Starting Page.
- Authorization with Clerk.
- Real-time database.
- Notion-style editor.
- Light and Dark mode.
- Infinite children documents.
- Trash can & soft delete.
- File upload
- File deletion
- File replacement
- Icons for each document (changes in real-time)
- Expandable and collapsable sidebar.
- Publish your note to the web.
- Cover image of each document.
- Recover deleted files.

## 📄 Pages

1. **Marketing Page**: Starting page that serves for marketing purposes.
2. **Clerk Sign-In/Sign-Up Page**: Displays Clerk Sign-in or Sign-up form.
3. **Main User Page**: Main page with main User interface.

## 🛠️ Technologies Used

- **NextJS 14**: A React framework for building server-rendered and static websites, offering features like routing, data fetching, and image optimization.
- **TypeScript**: A superset of JavaScript that adds optional static typing for better code maintainability and catching errors early.
- **TailwindCSS**: A utility-first CSS framework that provides a rapid way to style web applications.
- **Shadcn**: A collection of beautifully designed re-usable components that you can copy and paste into your apps.
- **Blocknote**: A React-based rich text editor for creating and editing text content with block-level formatting capabilities.
- **Clerk**: Manages user authentication and authorization flows in your web applications.
- **Edgestore**: A serverless data storage solution that allows you to store and retrieve data at the edge of the network, closer to users.
- **Convex**: A real-time backend platform that simplifies data management and synchronization for web applications, offering features like automatic data retrieval and updates.
- **Sonner**: A specialized JavaScript library for creating customizable and unobtrusive notification messages on websites.
- **Zod**: A type-safe data schema validation library for TypeScript that ensures data integrity and prevents errors by checking data against pre-defined rules.
- **Zustand**: A lightweight state management library for React applications that offers a simple API for managing application state in a centralized location.

## 🚀 Installation

To install and run this project locally on your machine, follow the steps below.

1. Clone the repository:

```bash
git clone https://github.com/MarkiyanCh1/noteforgehub.git
```

2. Navigate into the project directory:

```bash
cd noteforgehub
```

3. Install dependencies:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
CONVEX_DEPLOYMENT=

NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

**Setup Convex**

```shell
npx convex dev
```

4. Start the application:

```bash
npm run dev
```

The application will start running on http://localhost:3000.

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

---

## If you find this project useful, please consider giving it a star ⭐. Your support is greatly appreciated!

Happy coding! 💻
