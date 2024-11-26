**DocsSphere**
================

A modern web application leveraging Next.js, Clerk for authentication, Liveblocks for real-time collaboration, and Radix UI for accessible components. The project is styled with TailwindCSS and includes features like collaborative editing, dialog interactions, and more.

**Features**
------------

*   🔐 **User Authentication:** Powered by [Clerk](https://clerk.dev/) for seamless and secure user management.
    
*   📝 **Collaborative Editing:** Real-time collaboration using [Liveblocks](https://liveblocks.io/) with Lexical editor integration.
    
*   🎨 **Modern UI Design:** Built with [Radix UI](https://www.radix-ui.com/) components and styled using [TailwindCSS](https://tailwindcss.com/).
    
*   ⚡ **Rich Animations:** Smooth animations provided by tailwindcss-animate.
    
*   📊 **Real-Time Insights:** Leverage Liveblocks for real-time presence and collaboration tracking.
    

**Tech Stack**
--------------

### **Frontend Framework**

*   [Next.js](https://nextjs.org/) v14.2.5
    
*   [React](https://reactjs.org/) v18
    

### **Styling and UI**

*   [TailwindCSS](https://tailwindcss.com/) v3.4.1
    
*   [Radix UI Components](https://www.radix-ui.com/) (Dialog, Popover, Select, Label)
    

### **Real-Time Collaboration**

*   [Liveblocks](https://liveblocks.io/) (@liveblocks/client, @liveblocks/react, @liveblocks/react-lexical)
    

### **Authentication**

*   [Clerk](https://clerk.dev/) (@clerk/nextjs, @clerk/themes)
    

### **Other Libraries**

*   [Lucide Icons](https://lucide.dev/)
    
*   [Lexical](https://lexical.dev/) (@lexical/react)
    
*   [Sentry](https://sentry.io/) for error monitoring and performance tracking
    
*   [nanoid](https://github.com/ai/nanoid) for unique ID generation
    

**Getting Started**
-------------------

### 1\. Clone the Repository

git clone https://github.com/yourusername/project-name.git  cd project-name   `

### 2\. Install Dependencies

Make sure Node.js and npm are installed. Then run:

npm install   `

### 3\. Set Environment Variables

Create a .env.local file in the root directory and configure the following variables:

NEXT_PUBLIC_CLERK_FRONTEND_API= 

 NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=

  NEXT_PUBLIC_SENTRY_DSN=   `

### 4\. Run the Development Server

npm run dev   `

The app will be available at https://docssphere.vercel.app/sign-in.

**Scripts**
-----------

npm run dev   Starts the development server.

npm run build   Builds the project for production. 

npm run start   Runs the production build.

npm run lint   Lints the codebase using ESLint.

**Dependencies**
----------------

### Core Dependencies:

*   next: ^14.2.5
    
*   react: ^18
    
*   react-dom: ^18
    

### Styling and UI:

*   tailwindcss: ^3.4.1
    
*   tailwindcss-animate: ^1.0.7
    
*   @radix-ui/react-\*: (Dialog, Icons, Label, Popover, Select, Slot)
    

### Collaboration and State Management:

*   @liveblocks/client: ^2.3.0
    
*   @liveblocks/react: ^2.3.0
    
*   @liveblocks/react-lexical: ^2.3.0
    

### Authentication and Theming:

*   @clerk/nextjs: ^5.2.4
    
*   @clerk/themes: ^2.1.12
    

### Developer Utilities:

*   typescript: ^5
    
*   eslint: ^8
    
*   eslint-config-next: 14.2.5
    

**Development Tools**
---------------------

*   **TypeScript:** Enforces type safety and ensures maintainability.
    
*   **ESLint:** Maintains code consistency and quality.
    
*   **PostCSS:** Enhances styling workflows for TailwindCSS.
    

**Contributing**
----------------

We welcome contributions! To get started:

1.  Fork the repository.
    
2.  bashCopy codegit checkout -b feature-name
    
3.  bashCopy codegit commit -m "Add your message here"
    
4.  bashCopy codegit push origin feature-name
    
5.  Open a pull request.
    

**License**
-----------

This project is licensed under the MIT License. See the LICENSE file for more details.

**Acknowledgements**
--------------------

*   [Clerk](https://clerk.dev/) for authentication.
    
*   [Liveblocks](https://liveblocks.io/) for real-time collaboration tools.
    
*   [Radix UI](https://www.radix-ui.com/) for accessible UI components.
    
*   [TailwindCSS](https://tailwindcss.com/) for its powerful styling framework.
