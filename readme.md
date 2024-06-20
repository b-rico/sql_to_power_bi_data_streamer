# SQL to Power BI Data Streamer

## Overview
SQL to Power BI Data Streamer is a PowerShell-based solution that streams data from a SQL Server database to a Power BI dataset in real-time. This project allows you to push data directly from your SQL database to Power BI using the Power BI REST API, enabling real-time data visualization and analysis.

## Prerequisites
- SQL Server instance with accessible database
- Power BI account with a streaming dataset created
- PowerShell installed on your machine

## Setup Instructions

### Configuration

1. Clone the repository:
   ```bash
   git clone https://github.com/username/SQL-to-Power-BI-Data-Streamer.git
   cd SQL-to-Power-BI-Data-Streamer
2. Open the script scripts/stream_data_to_powerbi.ps1 and update the following placeholders with your actual values:
    <ServerName>
    <DatabaseName>
    <TableName>
    <workspace>
    <dataset>
    <your_API_key>
3. Running the Script
    To run the PowerShell script, execute the following command in your terminal:
        powershell -File scripts/stream_data_to_powerbi.ps1

4. Directory Structure
    SQL-to-Power-BI-Data-Streamer/
    │
    ├── scripts/
    │   └── stream_data_to_powerbi.ps1
    │
    ├── README.md
    ├── LICENSE
    └── .gitignore

## Contact

For any questions or issues, please contact Bert Rico at brico.git@gmail.com.