# Expense Management Frontend

A modern, feature-rich expense management system built with **React**, **Redux Toolkit**, **Material UI**, and **Vite**.

---

## 🚀 Features

- **Authentication**
  - Secure login and registration
  - Role-based access (Employee, Manager, Admin)
  - Forgot password support

- **Dashboard**
  - Personalized welcome and statistics
  - Quick actions for common tasks
  - Recent expenses and pending approvals overview

- **Expense Management**
  - Create, edit, and delete expenses
  - View all expenses in a sortable, filterable table
  - Attach categories and descriptions to expenses

- **Approvals**
  - Managers/Admins can view and approve/reject pending expenses
  - Approval workflow and status tracking

- **Analytics & Reports**
  - Visual analytics dashboard with charts (expenses trends, category breakdown, etc.)
  - Download reports as Excel files directly from the frontend
  - Filter and analyze expenses by date, category, and more

- **User Management (Admin)**
  - View all users in the system
  - Add new users via a modal form
  - Assign roles (Employee, Manager, Admin)

- **Modern UI/UX**
  - Responsive design with Material UI
  - Beautiful login page with gradient background and animations
  - Sidebar navigation with role-based menu items
  - Toast notifications for feedback

- **Security**
  - JWT-based authentication
  - Protected and role-based routes

---

## 🛠️ Tech Stack

- **React 18**
- **Redux Toolkit**
- **Material UI 5**
- **Vite**
- **React Router v6**
- **Axios**
- **Recharts, Chart.js** (for analytics)
- **xlsx** (for Excel export)
- **jsPDF** (for PDF export, optional)
- **date-fns** (date formatting)

---

## 📦 Getting Started

1. **Install dependencies**
   ```sh
   npm install
   ```

2. **Start the development server**
   ```sh
   npm run dev
   ```

3. **Build for production**
   ```sh
   npm run build
   ```

---

## 📁 Project Structure

- `src/pages/` — All main pages (Dashboard, Expenses, Approvals, Analytics, Reports, Users, Auth)
- `src/components/` — Layout, protected routes, and reusable UI components
- `src/store/` — Redux slices and store configuration
- `src/api/` — API utilities

---

## 📝 Customization

- **API URLs**: Update API endpoints in the `src/api/` files as needed.
- **Roles & Permissions**: Adjust role logic in `RoleBasedRoute` and Redux slices.
- **UI**: Customize Material UI theme in `src/theme.js` (if present).

---

## 🙏 Credits

- [Material UI](https://mui.com/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [Vite](https://vitejs.dev/)
- [SheetJS/xlsx](https://sheetjs.com/)
- [jsPDF](https://github.com/parallax/jsPDF)

---

## 📣 Contributing

Pull requests and issues are welcome! Please open an issue to discuss your ideas or report bugs.
