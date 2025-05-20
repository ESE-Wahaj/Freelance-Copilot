# 🚀 Freelance Copilot

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Laravel](https://img.shields.io/badge/Laravel-12-FF2D20?style=flat&logo=laravel&logoColor=white)](https://laravel.com)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=flat&logo=bootstrap&logoColor=white)](https://getbootstrap.com)

A professional, lightweight **Client Management System (Mini-CRM)** built with **Laravel** for freelancers, small agencies, and businesses to manage clients, projects, interactions, and reminders efficiently.

![Freelance Copilot Dashboard](/screenshots/dashboard.png)

## ✨ Features

### 👥 Client Profile Management
- Create and manage comprehensive client profiles
- Store essential contact information: Name, Email, Phone, Company
- Add detailed notes for each client
- Track client status and relationship history
- Organize clients by categories or tags

### 📊 Project Management
- Create multiple projects per client
- Set project budgets and track expenses
- Monitor project deadlines with visual indicators
- Update project status (Pending, Ongoing, Completed, Cancelled)
- Add project-specific notes and requirements

### 💬 Interaction Logs
- Record all client communications in one place
- Log different interaction types (calls, emails, meetings)
- Set follow-up flags for important interactions
- Search through interaction history
- Track conversation outcomes

### ⏰ Reminders System
- Create smart reminders for follow-ups and deadlines
- Receive notification alerts for upcoming tasks
- Set recurring reminders for regular check-ins
- Prioritize reminders by importance
- Mark reminders as completed

### 📄 PDF Report Generation
- Generate professional PDF reports for clients and projects
- Customize report content and layout
- Include project statistics and progress indicators
- Download or email reports directly to clients
- Create financial summaries and invoices

### 🔍 Search & Filter
- Powerful search functionality across all data
- Filter clients by project status, budget range, or deadline
- Sort interactions by date, type, or outcome
- Save frequent searches for quick access
- Export filtered results to CSV

### 🔒 User-Specific Data Protection
- Role-based access control
- Each user can only view and manage their assigned clients
- Secure authentication using Laravel Breeze
- Activity logging for audit purposes
- Two-factor authentication support

### 💻 Modern UI
- Clean, intuitive dashboard
- Responsive design works on desktop and mobile
- Dark/light mode toggle
- Customizable UI themes
- Accessibility-friendly interface

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| **Backend Framework** | Laravel 12 |
| **Frontend** | Bootstrap 5, Blade Templates |
| **Database** | MySQL |
| **PDF Generation** | DomPDF Package |
| **Authentication** | Laravel Breeze |
| **Icons** | Font Awesome 6 |
| **Charts** | Chart.js |

## 📋 Requirements

- PHP 8.2+
- Composer
- MySQL 8.0+
- Node.js & NPM (for asset compilation)

## 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ese-wahaj/freelance-copilot.git
   cd freelance-copilot
   ```

2. Install PHP dependencies:
   ```bash
   composer install
   ```

3. Install NPM dependencies:
   ```bash
   npm install && npm run dev
   ```

4. Create .env file:
   ```bash
   cp .env.example .env
   ```

5. Generate application key:
   ```bash
   php artisan key:generate
   ```

6. Configure your database in .env file and run migrations:
   ```bash
   php artisan migrate
   ```

7. Optional: Seed the database with sample data:
   ```bash
   php artisan db:seed
   ```

8. Start the development server:
   ```bash
   php artisan serve
   ```

## 📸 Screenshots

<div align="center">
  <img src="/screenshots/clients-view.png" alt="Clients List" width="48%">
  <img src="/screenshots/project-details.png" alt="Project Details" width="48%">
</div>
<div align="center">
  <img src="/screenshots/interaction-log.png" alt="Interaction Log" width="48%">
  <img src="/screenshots/reminders.png" alt="Reminders" width="48%">
</div>

## 📊 Database Schema

![Database Schema](/screenshots/database-schema.png)

## 🚀 Usage

After installation, create your account and start adding clients and projects. The dashboard provides an overview of your active projects, upcoming deadlines, and pending reminders.

Check out the [User Guide](/docs/USER_GUIDE.md) for more detailed instructions.

## 🧪 Testing

Run the test suite with:
```bash
php artisan test
```

## 🛣️ Roadmap

- [ ] Email integration for client communications
- [ ] Invoice generation and payment tracking
- [ ] Time tracking for billable hours
- [ ] Client portal for project updates
- [ ] Mobile app version

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Wahaj** - [GitHub Profile](https://github.com/ese-wahaj)

## 🙏 Acknowledgements

- [Laravel](https://laravel.com) - The PHP framework used
- [Bootstrap](https://getbootstrap.com) - Frontend framework
- [DomPDF](https://github.com/dompdf/dompdf) - PDF generation library
- [Chart.js](https://www.chartjs.org) - JavaScript charting library
- [Font Awesome](https://fontawesome.com) - Icons library
