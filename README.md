AWS Bedrock Finance Agent

Built an AI-powered finance assistant using Amazon Bedrock Agents and the Amazon Nova Lite foundation model. The agent analyzes financial transaction data from a CSV file, categorizes expenses, calculates spending across different categories, and generates personalized budgeting recommendations using natural language prompts.

Architecture

Amazon Bedrock → Amazon Bedrock Agent → Amazon Nova Lite → Code Interpreter → Transaction CSV → Expense Analysis → Budget Recommendations

Project Overview

Created an AI-powered finance assistant using Amazon Bedrock by configuring an Amazon Bedrock Agent with the Amazon Nova Lite foundation model and enabling the built-in Code Interpreter for data analysis. Uploaded a CSV dataset containing financial transaction records and instructed the agent to automatically categorize expenses, calculate spending across different categories, identify spending patterns, and generate personalized monthly budgeting recommendations through natural language prompts. Validated the solution by interacting with the agent and verifying the generated financial analysis and budgeting insights.

Technologies Used

Amazon Bedrock, Amazon Bedrock Agents, Amazon Nova Lite, AWS IAM, Code Interpreter, CSV, Artificial Intelligence (AI), Generative AI

Project Workflow

Created the Bedrock Agent

Opened Amazon Bedrock and selected the Amazon Nova Lite foundation model from the Model Catalog.

Created a new Bedrock Agent, configured its execution role, and completed the initial agent configuration.

Configured the foundation model, enabled the built-in Code Interpreter, and provided detailed instructions describing how the agent should analyze financial transaction data.

The agent was configured to:

Categorize expenses
Calculate spending by category
Analyze spending behaviour
Recommend monthly budgets

Prepared the Bedrock Agent to compile the latest configuration before testing.

Verified that the preparation completed successfully.

Uploaded a CSV file containing financial transaction records.

The Code Interpreter automatically read and processed the uploaded dataset.

Submitted prompts asking the agent to analyze spending habits.

The agent automatically:

Read the uploaded CSV
Categorized transactions
Calculated spending totals
Grouped expenses by category
Generated a financial summary

Asked the AI agent to recommend monthly budgets based on historical spending data.

The agent generated personalized budgeting recommendations and highlighted areas where spending could be optimized.

AWS Resources Used

Amazon Bedrock, Amazon Bedrock Agents, Amazon Nova Lite Foundation Model, AWS IAM ,Key Concepts Practiced, Amazon Bedrock, Foundation Models, AI Agents, Prompt Engineering, Code Interpreter, Natural Language Processing, Financial Data Analysis, AI-powered Budget Recommendations

What I Learned

How to build AI agents using Amazon Bedrock.
How foundation models process natural language prompts.
How the Code Interpreter analyzes structured datasets such as CSV files.
How Amazon Bedrock Agents combine foundation models with built-in tools to automate business workflows.
How prompt design directly impacts the quality of AI-generated responses.
