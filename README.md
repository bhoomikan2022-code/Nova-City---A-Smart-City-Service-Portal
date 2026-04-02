Overview
Nova City Portal is a smart city service management application that allows citizens to report city-related issues and enables administrators to manage, visualize, and analyze the reported issues.

The portal integrates a full-stack Java/Spring Boot backend, JSF/XHTML frontend, and ML-powered insights via a Python FastAPI service.

Users can:

Submit issues like water, transport, electricity, etc.
View status and updates for their submitted issues.
Rate issues after resolution.
Admins can:

View all submitted issues.
Track metrics like total issues, resolved/pending counts.
Visualize trends and category distributions via charts.
Fetch ML insights for issue descriptions (sentiment analysis, trends).
Technologies Used
Layer	Technology
Backend	Java, Spring Boot, Spring Security, Hibernate/JPA
Frontend	JSF, XHTML, CSS, JavaScript, Chart.js
Database	MySQL
ML Service	Python, FastAPI
External Assets	Google Fonts, Flaticon icons, Chart.js library
Features
User Features:

Register and login securely.
Submit new city issues with description.
View list of submitted issues with statuses.
Rate resolved issues.
Receive sentiment-based ML insights.
Admin Features:

Access a dedicated admin dashboard.
Monitor total, pending, and resolved issues.
View most reported categories.
Analyze trends with interactive charts.
Manage issues and view ML-generated analytics.
