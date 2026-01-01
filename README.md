# AtliQ Hospitality BI Dashboards

This repository contains two Power BI dashboards designed for AtliQ Hospitality to monitor performance across cities, room classes, and booking platforms.

## 📊 Dashboards

### 1. Key Insights Dashboard
- **Purpose:** High-level overview of revenue, occupancy, ratings, and reliability across cities.
- **Filters:** Month, City, Room Class
- **Highlights:**
  - Revenue: $1.71bn
  - Occupancy: 57.87%
  - Average Rating: 36.19
  - Mumbai: Most Reliable City
  - Visuals: RevPAR vs Cancellation %, Ratings by City, Bookings by Day Type

### 2. Summary Dashboard
- **Purpose:** Operational KPIs with week-over-week trends and platform performance.
- **Filters:** Month, City, Room Type
- **Highlights:**
  - Revenue: $1.7bn (WoW -82%)
  - RevPAR: 7.35K (WoW +28%)
  - ADR: 12.70K
  - DSRN: 2.53K
  - Platform Mix: makemytrip, booking.com, direct, goibibo, trip.com

## 📁 Repository Structure

- `/powerbi`: Contains `.pbix` files for both dashboards.
- `/assets`: Screenshots for quick reference.
- `/docs`: Metric definitions and dashboard specs.
- `/sql`: Supporting queries used in backend or validation.

## 📌 Metrics Dictionary

See [`docs/metrics_dictionary.md`](docs/metrics_dictionary.md) for definitions of:
- Revenue
- Occupancy %
- ADR
- RevPAR
- Cancellation %
- Average Rating
- DSRN / DBRN / DURN

## 🛠️ Requirements

- Power BI Desktop
- PostgreSQL or Excel backend (depending on your data source)
- Optional: Metabase for cross-platform visualization

## 📷 Screenshots

![Summary](https://github.com/Mdkamrulislam54/Hospitality-Domain-dashboard/blob/main/Hospitality%20Domain%20Dashboard-%20Summary.png)
![Key Insights](https://github.com/Mdkamrulislam54/Hospitality-Domain-dashboard/blob/main/Hospitality%20Domain%20dashboard%20-%20Key%20Insights.png)

