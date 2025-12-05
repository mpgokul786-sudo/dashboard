# dashboard
Tech Stack:

- Angular 20 (Standalone bootstrap)
- TypeScript
- SCSS
- ApexCharts via ng-apexcharts
- Local JSON files (mock backend)

📁 Project Structure

src/
  app/
    app.ts
    app.config.ts
    dashboard/
      dashboard.ts       // Component logic, JSON loading, chart config, filters
      dashboard.html     // Dashboard layout (toolbar, cards, charts)
      dashboard.scss     // Component styling + light/dark theme
  assets/
    data/
      dashboard_2024.json
      dashboard_2025.json
  main.ts

Dashboard Library:

# npm install apexcharts ng-apexcharts
