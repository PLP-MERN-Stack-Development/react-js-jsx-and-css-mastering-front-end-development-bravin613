# AI Task Master - Intelligent Todo List Application

A modern, feature-rich task management application built with React, Tailwind CSS, and Vite. 



## Features

### Core Functionality
- **Task Management**: Add, complete, and delete tasks with persistent storage
- **Smart Filtering**: Filter tasks by All, Active, or Completed status
- **Real-time Statistics**: Track total, active, and completed tasks
- **Local Persistence**: Tasks saved automatically using localStorage
- **API Integration**: Fetch and display user data from JSONPlaceholder API
- **Search Functionality**: Search users by name or email
- **Pagination**: Navigate through API results with ease

### UI/UX Features
- **Dark Mode**: Seamless theme switching with system preference detection
- **Responsive Design**: Mobile-first design that works on all screen sizes
- **Smooth Animations**: Beautiful transitions and micro-interactions
- **Modern Icons**: Lucide React icons for a consistent look
- **Gradient Backgrounds**: Eye-catching color schemes
- **Custom Font**: Jost font family for a modern aesthetic

### Technical Highlights
- **Component Architecture**: Reusable, maintainable components
- **Custom Hooks**: useLocalStorage hook for data persistence
- **Context API**: Global theme management
- **React Router**: Client-side routing for SPA experience
- **Loading States**: Elegant loading indicators
- **Error Handling**: Comprehensive error management

## Tech Stack

- **React 18.3.1** - Modern UI library with hooks
- **Vite 5.4.2** - Next-generation frontend tooling
- **Tailwind CSS 3.4.1** - Utility-first CSS framework
- **React Router DOM** - Declarative routing
- **Lucide React** - Beautiful icon library
- **JSONPlaceholder API** - Free REST API for testing


## Usage Guide

### Task Manager

1. **Adding Tasks**
   - Navigate to the Task Manager page
   - Type your task in the input field
   - Press Enter or click "Add Task"

2. **Managing Tasks**
   - Click the circle icon to mark tasks as complete
   - Click "Delete" to remove tasks
   - Use filter buttons to view All, Active, or Completed tasks

3. **Statistics**
   - View real-time stats for total, active, and completed tasks
   - All data persists in localStorage

### API Demo

1. **Viewing Users**
   - Navigate to the API Demo page
   - User data loads automatically from JSONPlaceholder

2. **Searching**
   - Use the search bar to filter users by name or email
   - Results update in real-time

3. **Pagination**
   - Navigate through pages using pagination controls
   - 6 users displayed per page

### Theme Switching

- Click the sun/moon icon in the navbar
- Theme preference saved in localStorage
- Seamless transition between light and dark modes



## Deployment

### Vercel

live link - https://ai-task-master-1.vercel.app/



## Screenshots

### Landing Page
![Landing Page](AITaskMaster/public/Screenshot%202025-10-24%20183456.png)
![Landing Page](./public/Screenshot%202025-10-24%20183518.png)
### Task Manager
![Task Manager](AITaskMaster/public/Screenshot%202025-10-24%20183615.png)
## completed tasks
![Task Manager](AITaskMaster/public/Screenshot%202025-10-24%20183628.png)
### API Demo
![API Demo](AITaskMaster/public/Screenshot%202025-10-24%20183644.png)

### Dark Mode
![Dark Mode](AITaskMaster/public/Screenshot%202025-10-24%20183518.png)

## API Integration Details

### JSONPlaceholder API

- **Endpoint**: `https://jsonplaceholder.typicode.com/users`
- **Method**: GET
- **Response**: Array of user objects
- **Fields Used**: name, email, phone, company

### Error Handling

- Loading states with spinner
- Error messages with retry functionality
- Network error handling



## Future Enhancements

- Task categories and tags
- Due dates and reminders
- Drag and drop task reordering
- Task priority levels
- Export tasks to CSV/JSON
- Collaborative task sharing
- Backend integration
- User authentication
- Task analytics dashboard



**Built with React, Tailwind CSS, and Vite**

Developed by Bravin for Week 3 React.js Assignment
