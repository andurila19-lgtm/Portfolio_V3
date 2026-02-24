# Portfolio V5

Hello everyone! 👋

Let me introduce myself, I'm **Anduril Ahmad Silvera Burhani**. I am a Full Stack Developer & Cyber Security Student.

## 🚀 Live Demo

**Website Link:** [https://anduril.web.id/](https://anduril.web.id/)

## 🛠️ Tech Stack

This project is built using modern web technologies:

  - **ReactJS** - Frontend framework
  - **Tailwind CSS** - Utility-first CSS framework
  - **Supabase** - Backend for portfolio data, certificates, and comment system
  - **AOS** - Animate On Scroll library
  - **Framer Motion** - Animation library
  - **Lucide** - Icon library
  - **Material UI** - React component library
  - **SweetAlert2** - Beautiful alert dialogs

## 📋 Prerequisites

Before running this project, ensure you have the following installed:

  - **Node.js** (version 14.x or higher)
  - **npm** or **yarn** package manager

## 🏃‍♂️ Getting Started

Follow these steps to run the project locally:

### 1\. Clone the Repository

```bash
git clone https://github.com/andurila19-lgtm/Portfolio_V3.git
cd Portofolio_V5
```

### 2\. Install Dependencies

```bash
npm install
```

If you encounter peer dependency issues, use:

```bash
npm install --legacy-peer-deps
```

### 3\. Run the Development Server

```bash
npm run dev
```

### 4\. Open in Browser

Access the application through the link displayed in your terminal (usually `http://localhost:5173`).

## 🏗️ Building for Production

To create a production-ready build:

1.  Run the build command:

    ```bash
    npm run build
    ```

2.  The build files will be saved in the `dist` folder. Upload this folder to your hosting server.

## ⚙️ Configuration (Supabase)

All backend data for this project (portfolio, certificates, and comments) is managed by Supabase.

### 1\. Create Supabase Project

  - Go to [Supabase](https://supabase.com/) and create a new project.
  - Keep your **Project URL** and **anon public key** handy. You can find them in **Settings \> API**.

### 2\. Setup Database Tables & Policies

Run the all-in-one SQL script found in `supabase_setup.sql` in your Supabase **SQL Editor**. This will set up all necessary tables, security policies, storage, and also insert example projects.

### 3\. Enable Realtime (for Comment System)

  - Go to **Table Editor > portofolio_comments**.
  - Enable Realtime for the `portfolio_comments`.

## 🔧 Environment Variables Setup

Create a file named `.env` in the root of your project and add your Supabase credentials.

```env
# Supabase Configuration
VITE_SUPABASE_URL=your-supabase-url
VITE_SUPABASE_ANON_KEY=your-supabase-anon-key
```

**Important:**

  - All environment variables must be prefixed with `VITE_` for Vite to access them.
  - Restart your development server after creating or modifying the `.env` file.
  - **Never** commit your `.env` file to version control. Ensure it's listed in your `.gitignore` file.

## 🚨 Troubleshooting

If you encounter issues while running the project:

  - Ensure Node.js is correctly installed.
  - Verify you're in the correct project directory.
  - Check that all dependencies are installed without errors.
  - Make sure your Supabase configuration in the `.env` file is correct and the server has been restarted.
  - Clear your browser cache and try again.

## 📝 Usage & Credits

We would appreciate it if you decide to use this project. Please include proper credit when using it. Thank you\! 🙏

## 📞 Contact

If you have any questions or need help with the setup, feel free to reach out\!

**Anduril Ahmad Silvera Burhani**

  - Website: [https://anduril.web.id/](https://anduril.web.id/)
  - GitHub: [andurila19-lgtm](https://github.com/andurila19-lgtm/Portfolio_V3)

-----

Thanks to
- https://lottiefiles.com/free-animation/coding-NWhbxMOVgP
- Claude
- Antigravity AI

⭐ If this project helped you, please consider giving it a star on GitHub\!
