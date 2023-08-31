### Objective:
The objective of this use case is to facilitate the seamless transfer of telemetry data from a third-party Internet of Things (IoT) device, connected to a vehicle, to Azure cloud infrastructure. The data, transmitted in JSON format, will first be validated for completeness and correctness before being stored in a SQL database. This validated data will serve as a valuable resource for Customer’s Data Science team for analysis and insights.

### Overview:
1. Data Source:

• Third-Party IoT Device Vehicles are equipped with third-party IoT devices capable of collecting and transmitting telemetry data.
• Telemetry data is sent in JSON format.

2. Data Transmission: AWS Cloud

• The telemetry data is initially sent to the AWS cloud, acting as an intermediary.

3. Data Transfer: AWS to Azure Cloud

• The primary task is to move data from the third-party AWS cloud to Azure cloud infrastructure.
• This transfer process ensures that data remains securely and efficiently accessible to Customer.

4. Data Validation: JSON Integrity
   
• Before the telemetry data is processed further, it undergoes validation.
• The validation step checks for completeness and correct JSON formatting.
• Any incomplete or incorrectly formatted JSON data is rejected.

5. Data Storage: SQL Database

• Validated telemetry data is stored in a SQL database.
• This structured storage facilitates organized and efficient data management.

6. Utilization: Data Science Team
• The stored data in the SQL database serves as a crucial resource for Data Science team.
• Data analysts and scientists utilize this data for various analyses, insights, and decision-making
processes.

### Benefits:
• Seamless integration of telemetry data from IoT devices to Customer’s Azure cloud.
• Ensured data integrity through validation, minimizing the risk of incorrect or incomplete data.
• Centralized storage of telemetry data in a SQL database for easy access and analysis.
• Empowering the Data Science team with valuable data for informed decision-making.
