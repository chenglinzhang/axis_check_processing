```
Input Node (Data Ingestion): 
    This workflow accepts transaction data. It can connect to Google Drive files, such as CSVs and Sheets, or integrate with real-time data sources.
Processing Nodes (AI Analysis):
    Data Preprocessing: A prompt directs the AI to clean data, handle missing values, and normalize transaction amounts.
    Feature Engineering: The AI analyzes behavioral patterns to identify potential red flags. These patterns include location, time, and frequency.
    Classification/Detection: Using Gemini models, the tool identifies fraudulent transactions. This is based on deviation from typical patterns.
Human-in-the-Loop Node: The workflow allows human review. The AI presents high-risk transactions for approval or rejection.
    Output Node (Action & Reporting):
    Action: The system can automatically flag transactions.
Reporting: The output can be written directly into a Google Doc, Slide, or integrated into a dashboard for analysts. 
```

