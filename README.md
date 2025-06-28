# DeltaDesk
##DeltaDesk is a modern, open-source desktop interface that allows users to explore, query, and manage Delta Lake tables stored in Azure Data Lake Storage Gen2 (ADLS) using cloud-based compute engines like Databricks SQL Warehouse and Azure Synapse Analytics—all within a smooth, SSMS-style experience.

⸻

🚀 Features
	•	🔗 Connect to ADLS Gen2 using Azure AD or SAS credentials
	•	🧠 Auto-detect Delta Tables from given storage paths
	•	💬 Run SQL Queries against Delta Lake using Databricks or Synapse compute
	•	📊 Tabular Result Viewer with export options to CSV or Excel
	•	🧭 Schema Explorer to browse table structures and metadata
	•	🧱 Mimics SQL Server Management Studio (SSMS) UI and workflow
	•	🔒 Built-in authentication with secure token handling

⸻

💡 Why DeltaDesk?

DeltaDesk bridges the usability gap between powerful cloud data platforms and the simplicity of local query tools. Instead of navigating complex cloud consoles or notebooks, data engineers and analysts can now explore Delta Lake with ease — like they’re used to with traditional SQL tools.

⸻

🛠️ Architecture Overview
	•	Frontend: Electron + HTML/CSS + JavaScript (SSMS-style layout)
	•	Backend: Node.js service layer
	•	Compute Integration: Databricks SQL Warehouse / Synapse (via REST APIs)
	•	Storage Integration: ADLS Gen2 (OAuth/SAS authentication)
	•	Data Protocol: Delta Lake via cloud-native compute routing