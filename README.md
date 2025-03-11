# 🚀 TaskFlow

**TaskFlow** is a powerful project management tool built using modern technologies like **Next.js**, **PostgreSQL**, **Prisma**, **ShadCN UI**, and **Clerk** for authentication. TaskFlow helps teams efficiently manage tasks, track progress, and collaborate effectively using agile frameworks like **Scrum** and **Kanban**.

---

## 🌟 **Features**
### ✅ **User Authentication**  
- Secure and easy sign-in/sign-up with **Clerk**.  
- Role-based access control for managing permissions.  

### ✅ **Task and Issue Tracking**  
- Create, update, and delete tasks with priority settings.  
- Assign tasks to team members and track status in real-time.  

### ✅ **Agile Boards**  
- **Scrum Board** – Manage sprints and backlog efficiently.  
- **Kanban Board** – Visualize task progress through different stages.  

### ✅ **Project Roadmaps**  
- Create high-level roadmaps to align team goals.  
- Adjust deadlines and priorities as the project evolves.  

### ✅ **Reporting and Analytics**  
- Track team performance with detailed reports and insights.  
- Monitor task completion rates and identify bottlenecks.  

### ✅ **Custom Workflows**  
- Define and customize workflows based on project needs.  
- Automate task transitions and notifications.  

### ✅ **User-Friendly UI**  
- Built with **ShadCN UI** for a clean and modern interface.  
- Fully responsive for seamless use on all devices.  

---

## 🛠️ **Tech Stack**
| Technology     | Description                                |
|---------------|--------------------------------------------|
| **Next.js**    | Frontend framework for fast, server-rendered React apps |
| **PostgreSQL** | Relational database for structured data storage |
| **Prisma**     | ORM for database interaction and migrations |
| **ShadCN UI**  | Modern and customizable UI components |
| **Clerk**      | Secure user authentication and session management |

---

## 🚀 **Installation and Setup**
### 1. **Clone the Repository**
```bash
git clone https://github.com/your-username/taskflow.git
cd taskflow
```

### 2. **Install Dependencies**
```bash
npm install
```

### 3. **Configure Environment Variables**
Create a `.env` file in the root directory with the following variables:
```
DATABASE_URL="postgresql://username:password@localhost:5432/taskflow"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
```

### 4. **Set Up the Database**
```bash
# Run migrations to set up your database schema
npx prisma migrate dev --name init

# Generate Prisma client
npx prisma generate
```

### 5. **Start the Development Server**
```bash
npm run dev
```
Your TaskFlow application should now be running at `http://localhost:3000`.

### 6. **Build for Production**
```bash
npm run build
npm start
```

## 📝 **Configuration Options**

### Database Configuration
- Update the `DATABASE_URL` in your `.env` file to connect to your PostgreSQL instance.
- You can use a local or hosted PostgreSQL database.

### Authentication Setup
1. Create an account at [Clerk.dev](https://clerk.dev)
2. Create a new application in the Clerk dashboard
3. Copy your API keys to the corresponding environment variables
4. Configure additional authentication options in the Clerk dashboard

## 🔧 **Troubleshooting**
- If you encounter database connection issues, verify your PostgreSQL credentials and ensure the service is running
- For authentication problems, check that your Clerk API keys are correct and properly configured
- Clear your browser cache if you experience UI inconsistencies after updates

## 🤝 **Contributing**
We welcome contributions to TaskFlow! Please follow these steps:

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request


## 📱 **Contact**
Maintained by [JAY PANDYA](https://github.com/1JAYPANDYA1). Feel free to reach out to me through GitHub or email for any queries.