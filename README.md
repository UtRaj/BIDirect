# BiDirect
--------
## Bidirectional ClickHouse & Flat File Data Ingestion Tool

## Overview Of The Project

This is Web App that helps in **bidirectional data transfer** between **ClickHouse Database  <----> Flat File**

---

## Specialities

1. Bidirectional Data Flow between ClickHouse to FlatFile.

 2. **JWT Authentication** for ClickHouse connections

3. Support for **CSV File**

4. View tables and columns from ClickHouse and preview them

5.  **Progress Indicator** and **record count display**

6. **Error Handling** with user-friendly messages (e.g., invalid credentials, connection failures, malformed CSV)

---

## Libraries and Frameworks Used

### Backend Frameworks

1. `express`: Web server

2. `@apla/clickhouse`: ClickHouse client for Node.js

3. `jsonwebtoken`: For handling JWT tokens

4. `csv-parser`, `fast-csv`: For reading/writing CSV files

### Frontend Frameworks

1. `React`: UI framework

2. `axios`: For API calls

---

## User Interface (UI) Flow

1. **Select Source**: Choose "ClickHouse" or "Flat File"
   
2. **Provide Connection Details** (ClickHouse host, port, user, JWT, etc.)
   
3. **Load Schema**: Fetch tables or columns
   
4. **Select Columns**: Choose which columns to ingest
   
5. **Choose Target**: Where the data should go (CSV or ClickHouse)
    
6. **Start Ingestion**
    
7. **View Results**: Ingestion complete message + record count

---


## Setup, Configuration & Run Instructions

1. Clone the Repository

2. Backend Setup

```

- cd .\Bi-server\
  
- npm install

- npm run dev

```

3. Frontend Setup

```
   
- cd .\Bi-client\
  
- npm install

- npm run dev

```

4. The frontend will be accessible at: http://localhost:5173
