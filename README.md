📊 Business Ledger CLI
🚀 Overview

Business Ledger CLI is a Java-based command-line application designed to track and analyze business financial transactions. Beyond simple bookkeeping, it provides insights into spending behavior through pattern detection and contextual tagging.

This project emphasizes clean architecture, extensibility, and modern Java practices.

✨ Key Features
💰 Transaction Management
Record deposits and payments
Structured transaction storage via CSV
Easy retrieval and display of financial records
🏷️ Smart Categorization
Filter transactions by categories such as:
Food
Investments
Leisure
Utilities
Enables quick financial breakdowns
📈 Behavioral Insights
Detect spending patterns:
Unusual spikes in expenses
Recurring vendors
Provides analytics similar to lightweight financial intelligence tools
🧠 Context & Mood Tagging
Attach mood and context to each transaction
Helps identify why money is being spent—not just where
Useful for behavioral and habit analysis
🛠️ How to Run
Open the project in IntelliJ IDEA (or any Java IDE)

Locate and run:

Main.java

Ensure the following file exists in the root directory:

transactions.csv
📂 Data Format

Transactions are stored in a pipe-delimited format:

date | time | description | vendor | amount | category | mood | context
Example:
2026-04-20|14:32|Lunch|Chipotle|-12.50|Food|Happy|Team outing
🧩 Architecture Highlights
Layered Design
Separation of concerns (CLI, services, data handling)
Service-Oriented Structure
Easily extendable for new features
Java Stream API
Efficient data filtering and transformation
Modular Components
Clean and maintainable codebase
💡 What Sets This Project Apart

This isn’t just a basic ledger—it introduces features that go beyond typical student projects:

Pattern Detection Engine
Identifies trends and anomalies in spending
Behavioral Tagging System
Combines financial data with emotional/contextual metadata
Scalable Design
Built with extensibility in mind for future enhancements
Modern Java Practices
Stream API, clean structure, and readable code
