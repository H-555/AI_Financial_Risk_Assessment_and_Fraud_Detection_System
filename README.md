# AI_Financial_Risk_Assessment_and_Fraud_Detection_System using Mistral
It monitors the transaction data, detects anomalies and suspicious pattern, validates it with Internal policies and suggests response/action by referring to internal alert_policies. Continuous monitoring of transaction data and autonomous action taking without human intervention will be enabled in future.

# Features:
Analyse the transaction data and detects anomalies and suspicious pattern (Uses RAG).

Validates the anomalies with internal policies (Uses RAG).

Suggests responses and Action to be taken with internal alert policies (Uses RAG).

# Requirements
Install the required dependencies:

pip install openai

pip install pyautogen

pip install langchain-community

pip install pandas

# How it Works?
Its has 3 main components:

anomaly_detector - Analyse the transaction data and detects anomalies and suspicious pattern using RAG.

policy_validator_agent - Validates the anomalies with internal policies using RAG

alerting_agent - Suggests responses and action to be taken with internal alert policies using RAG by providing details of AlertID, EscalationLevel (High, Moderate, Low), MitigationAction, NotifyTo and Explanation.
