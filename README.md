# AI-Powered Customer Support Agent

This project implements a multi-step, conversational AI agent using LangGraph to handle customer verification for a bank.

## Features
- **Greeter Agent**: Collects user details (name, phone, IBAN).
- **Verification Logic**: A reliable Python-based system that checks user details against a database using a 2/3 rule and a secret question.
- **Conversational Agent**: A final agent that assists the user once they are verified.

## Setup
1. Create a virtual environment: `python3 -m venv .venv`
2. Activate it: `source .venv/bin/activate`
3. Create a `.env` file and add your API keys (see `.env.example`).