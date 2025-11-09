# TaskMaster Pro

![React](https://img.shields.io/badge/React-18.2.0-blue.svg)
![Tailwind](https://img.shields.io/badge/Tailwind-3.3.3-38bdf8.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

> A beautiful, feature-rich task management application built with React and Tailwind CSS

[Live Demo](#) | [Report Bug](https://github.com/rohithreddy5250/taskmaster-pro/issues) | [Request Feature](https://github.com/rohithreddy5250/taskmaster-pro/issues)

## Features

- **Create, Edit, Delete Tasks** - Full CRUD operations
- **Priority Levels** - High, Medium, Low priority tasks
- **Categories** - Organize by Personal, Work, Shopping, Health
- **Due Dates** - Set deadlines for your tasks
- **Search & Filter** - Find tasks quickly
- **Dashboard Stats** - Track your productivity
- **Local Storage** - Tasks persist across sessions
- **Beautiful UI** - Modern glassmorphism design
- **Fully Responsive** - Works on all devices
- **Fast & Smooth** - Optimized performance

## Screenshots

![TaskMaster Pro Dashboard](https://via.placeholder.com/800x400/6366f1/ffffff?text=Add+Your+Screenshot+Here)

*Add actual screenshots of your application here*

##  Demo

Try it live: [TaskMaster Pro Demo](#)

##  Built With

- **React 18** - UI Framework
- **Tailwind CSS** - Styling
- **Lucide React** - Icons
- **Vite** - Build Tool
- **Local Storage API** - Data Persistence

## Installation

### Prerequisites

- Node.js 16+ and npm

### Setup

1. **Clone the repository**
```bash
git clone https://github.com/rohithreddy5250/taskmaster-pro.git
cd taskmaster-pro
```

2. **Install dependencies**
```bash
npm install
```

3. **Start development server**
```bash
npm run dev
```

4. **Open your browser**
```
http://localhost:5173
```

## Usage

### Creating a Task

1. Click the **"Add Task"** button
2. Fill in task details:
   - Title (required)
   - Description (optional)
   - Category
   - Priority level
   - Due date
3. Click **"Add Task"**

### Managing Tasks

- **Complete**: Click the circle icon to mark as done
- **Edit**: Click the edit icon to modify task details
- **Delete**: Click the trash icon to remove task

### Filtering & Search

- Use the search bar to find specific tasks
- Use the filter dropdown to view:
  - All tasks
  - Active tasks only
  - Completed tasks
  - Tasks by priority

## Project Structure

```
taskmaster-pro/
├── src/
│   ├── App.jsx          # Main application component
│   ├── main.jsx         # Entry point
│   └── index.css        # Global styles
├── public/
├── package.json
├── vite.config.js
├── tailwind.config.js
└── README.md
```

## Features in Detail

### Dashboard Statistics
- **Total Tasks**: Overall task count
- **Active**: Incomplete tasks
- **Completed**: Finished tasks
- **High Priority**: Urgent tasks needing attention

### Task Categories
-  **Personal** - Personal life tasks
-  **Work** - Professional tasks
-  **Shopping** - Shopping lists
-  **Health** - Health & fitness goals

### Priority Levels
- **High** - Urgent and important
- **Medium** - Important but not urgent
- **Low** - Can wait

## Deployment

### Deploy to Vercel

```bash
npm run build
# Deploy the dist/ folder to Vercel
```

### Deploy to Netlify

```bash
npm run build
# Drag and drop the dist/ folder to Netlify
```

##  Roadmap

- [ ] User authentication
- [ ] Cloud sync (Firebase/MongoDB)
- [ ] Recurring tasks
- [ ] Task reminders/notifications
- [ ] Subtasks
- [ ] Task sharing/collaboration
- [ ] Calendar view
- [ ] Mobile app
- [ ] Dark/Light theme toggle
- [ ] Export tasks (CSV, PDF)

##  Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Rohith Reddy**

- GitHub: [@rohithreddy5250](https://github.com/rohithreddy5250)
- LinkedIn: [rohithreddyy](https://linkedin.com/in/rohithreddyy)
- Email: rohithreddybaddam8@gmail.com

## Acknowledgments

- [Lucide Icons](https://lucide.dev/) for beautiful icons
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Vite](https://vitejs.dev/) for fast builds

## Stats

![GitHub Stars](https://img.shields.io/github/stars/rohithreddy5250/taskmaster-pro?style=social)
![GitHub Forks](https://img.shields.io/github/forks/rohithreddy5250/taskmaster-pro?style=social)

---

⭐ **If you like this project, please give it a star!**

**Made with ❤️ by Rohith Reddy**
