# Money Tracker App

A modern, responsive money tracking application built with React, TypeScript, and Tailwind CSS. Track your income and expenses with beautiful visualizations and detailed analytics.

![Money Tracker App](https://via.placeholder.com/800x400/1E40AF/FFFFFF?text=Money+Tracker+App)

## ✨ Features

- 📊 **Interactive Dashboard** - Visual overview of your financial health
- 💰 **Income & Expense Tracking** - Easy transaction management with categories
- 📈 **Analytics & Charts** - Spending patterns and monthly trends
- 🎯 **Savings Rate Calculator** - Track your financial goals
- 📱 **Responsive Design** - Works perfectly on desktop and mobile
- 💾 **Local Storage** - Your data persists between sessions
- 🇮🇳 **INR Currency** - Formatted for Indian Rupees

## 🚀 Quick Start

### Prerequisites

- Node.js 16+ 
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/money-tracker-app.git
   cd money-tracker-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
```

The built files will be in the `dist/` directory, ready for deployment.

## 🛠️ Tech Stack

- **Frontend**: React 18, TypeScript
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **Icons**: Lucide React
- **Storage**: Browser localStorage

## 📁 Project Structure

```
money-tracker-app/
├── public/
├── src/
│   ├── components/
│   │   ├── BalanceCard.tsx
│   │   ├── Dashboard.tsx
│   │   ├── IncomeList.tsx
│   │   ├── MonthlyTrend.tsx
│   │   ├── RecentTransactions.tsx
│   │   ├── SpendingChart.tsx
│   │   ├── TransactionForm.tsx
│   │   └── TransactionList.tsx
│   ├── types/
│   │   └── Transaction.ts
│   ├── App.tsx
│   ├── index.css
│   └── main.tsx
├── index.html
├── package.json
├── tailwind.config.js
├── tsconfig.json
└── vite.config.ts
```

## 🎨 Features Overview

### Dashboard
- Net balance overview
- Total income and expenses
- Savings rate calculation
- Monthly trends visualization
- Spending by category charts

### Transaction Management
- Add income and expenses
- Categorize transactions with icons
- Search and filter transactions
- Edit and delete transactions
- Date-based grouping

### Analytics
- Visual spending charts
- Monthly trend analysis
- Category-wise breakdowns
- Savings rate tracking

## 🚀 Deployment

### Netlify
1. Build the project: `npm run build`
2. Drag and drop the `dist/` folder to Netlify

### Vercel
1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect it's a Vite project
3. Deploy with default settings

### GitHub Pages
1. Install gh-pages: `npm install --save-dev gh-pages`
2. Add to package.json scripts:
   ```json
   "deploy": "gh-pages -d dist"
   ```
3. Run: `npm run build && npm run deploy`

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Icons by [Lucide](https://lucide.dev/)
- UI inspiration from modern fintech apps
- Built with [Vite](https://vitejs.dev/) and [React](https://reactjs.org/)

 📧 Contact

adhityanvembanat2617@gmail.com

Project Link: [https://github.com/yourusername/money-tracker-app](https://github.com/AdhityanV/moneytracker)
