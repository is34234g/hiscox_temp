# What are the next steps to go from a Jupyter Notebook to a productionised service?

Refactor the code into modular Python scripts or packages.
Use a REST API using frameworks like Flask for querying model
Containerize the application using Docker
Set up CI/CD pipelines for automated testing, deployment, and monitoring.
Deploy to cloud


# What are the considerations for ensuring the business can leverage it?
Explainability: Use tools like SHAP/feature importance plots.
Monitoring: Track model performance, data drift, and prediction quality over time. (built into most cloud providers)
Security & Compliance: Ensure data privacy, access control, and regulatory compliance (e.g. make sure our features dont include identifying charactersitics e.g ethinicity/name ).
User Interface: Provide dashboards or tools for non-technical users to interact with the model.

# What are the steps you would take to provide this to the business?

Present findings from the notebook to analysts/stakeholders in the businness for feedback/improvemennts/further analysis.
Build a prototype API and demonstrate it with real-time or batch predictions.
Train end-users and provide documentation for usage and interpretation.
Establish feedback loops for continuous improvement.

# Which traditional teams in a business would you need to speak to?

Sales/end customers who are going to use the model
Data Engineering: For data pipelines, storage, and access.
ML engineers: For deployment, infrastructure, and monitoring.
Risk & Compliance: regulatory alignment and model governance.
Product/Business Analysts: To align model outputs with business needs.
