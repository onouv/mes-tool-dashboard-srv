# mes-tool-dashboard-srv
A microservice to provide dashboard data for tools.

This service subscribes to various KPI value topics in the **`mes-bus`** and aggregates them to data that can be loaded by a dashboard. It provides various REST enpoints for that purpose. It interfaces to a **`mes-tool-dashboard-db`** data base to maintain the aggregated state.
