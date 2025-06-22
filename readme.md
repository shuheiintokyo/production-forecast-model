# Production Forecast Model

A comprehensive production planning and inventory management tool.

## Features
- 📊 Product lineup configuration
- 📈 Client forecast management
- 🏭 Factory production scheduling
- 📦 Material order planning
- 💾 Data persistence with localStorage
- 📥 Excel file import/export

## Live Demo
[View Live Application](https://your-app-name.vercel.app)

## Local Development
1. Clone the repository
2. Open `index.html` in a web browser
3. Upload your Excel configuration file
4. Start planning your production!

## Excel File Format
Your Excel file should contain:
- **Sheet 1**: "Product Lineup" - Product configurations
- **Sheet 2**: "ClientForcast" - 6-month demand forecast

## Timing Rules
- **Forecast**: Products needed at beginning of month
- **Material Orders**: Delivered next month, production starts month after
- **Production**: Added to inventory at end of month
- **Inventory**: Shows end-of-month amounts