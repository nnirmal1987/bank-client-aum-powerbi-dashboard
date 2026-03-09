# bank-client-aum-powerbi-dashboard
Power BI dashboard analyzing banking client portfolios, account balances, and segmentation (Platinum vs Basic) with many-to-many data modeling.

# Bank Client AUM Dashboard (Power BI)

## Project Overview
This project analyzes client relationships, portfolio performance, and assets under management (AUM) for a banking scenario. (Simulated synthetic data)

The goal was to design an executive dashboard providing insights into:
- Client segmentation (Platinum vs Basic)
- Account balances
- Portfolio distribution
- Advisor performance

## Data Model
A many-to-many relationship exists between Clients and Accounts.

To handle this, a bridge table (AccountClientLink) was used.

Portfolio → Client → AccountClientLink → Account

## Key Metrics
- Total AUM
- Existing Clients
- AUM by Client Group
- Average Balance per Client
- Accounts per Client

## Tools Used
- Power BI
- Power Query
- DAX
- Data Modeling (Bridge Table)

## Dashboard Pages
1. Executive Overview
2. Client Value & Segmentation
3. Portfolio & Advisor Performance

## Key Insights
- Platinum clients contribute a majority of total AUM.
- Client tenure correlates with higher account balances.
- Certain advisors manage disproportionately higher-value portfolios.

