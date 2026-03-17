# OpenClaw Agent - Newsletter Digest

This project implements an agent built with OpenClaw that processes newsletter emails and generates a structured digest using a Python script.

Instead of handling arbitrary messages, the agent focuses specifically on newsletters from different subscriptions and topics. It extracts relevant information from each email, filters noise, and compiles a concise report that summarizes the key content across all sources.

## Features
- Parsing of newsletter emails from multiple subscriptions
- Content filtering to remove irrelevant information
- Summarization of each newsletter
- Aggregation into a single structured report

## Tech Stack
- Python
- OpenClaw

## Usage
Run the digest script:

```bash
python scripts/digest.py
