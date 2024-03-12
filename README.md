# U5L03-1-CW---ERROR-LOGS---via-REGEX
Objective:
In this assignment, you will use Python and regular expressions to analyze a log file stored in JSON format. Your goal is to identify and extract all log entries with the level "ERROR," then save these entries into a CSV file for easy review and analysis.

Task:
Create a Python script that performs the following operations:

Read Log Entries: Open and read the content of logs.json, which contains log entries in JSON format.

Filter Error Logs: Use a regular expression to identify log entries with the level "ERROR." Consider the log level's exact text match in your regex pattern.

Write to CSV: For each "ERROR" log entry found, write the relevant data (timestamp, level, and message) to a new CSV file named error_logs.csv. Your CSV should include a header row with these column names.

Error Handling: Implement basic error handling to manage issues like missing files or read/write errors gracefully.

