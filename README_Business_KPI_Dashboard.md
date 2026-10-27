# Business KPI Dashboard — Customer Churn

## Objective
Interactive dashboard to explore churn, retention, monthly revenue exposure, average tenure, and customer segments.

## Included KPIs
- Churn rate = churned customers / filtered customers
- Retention rate = retained customers / filtered customers
- Monthly revenue at risk = sum of monthly charges for customers marked as churned
- Average tenure
- Customer count

## Interactive filters
Contract type, tenure segment, payment method, and customer ID search.

## Charts
Churn vs retention, churn rate by contract, monthly charges by churn status, tenure distribution, and churn rate by payment method.

## Run locally
Open `index.html` in a modern web browser with internet access (Plotly is loaded from a CDN).

## Publish with GitHub Pages
1. Upload `index.html` to the root of the public GitHub repository.
2. Open repository **Settings → Pages**.
3. Under Build and deployment, select **Deploy from a branch**.
4. Choose branch `main`, folder `/ (root)`, then Save.
5. Wait for the published URL shown on the Pages settings screen. It typically looks like `https://<username>.github.io/<repository>/`.
6. Open the published URL and test each filter before submitting the dashboard URL to Edvyro.

## Data limitations
The supplied dataset contains only 15 synthetic customer records. This dashboard is for demonstration and descriptive exploration, not operational forecasting. Revenue at risk is a simple monthly-charge sum, not predicted future loss.
