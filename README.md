# YouTube_Creator_Agentdemo

🎬 YouTube Creator AI Agent – Kaggle Day-5 Capstone Project
LLM + MCP + Memory + Tool-Based Agent (End-to-End Demo)

This repository contains my final capstone project for the Kaggle 5-Day AI Course.
I built a fully functional AI Agent using MCP (Model Context Protocol) + LLM + Session Memory to assist YouTube creators with content generation.

# 📌 Project Overview

Creators often struggle with:

Finding unique YouTube video ideas

Writing engaging scripts

Generating SEO-optimized descriptions

Summarizing long topics

Maintaining consistency across videos

My agent solves all of these.

This agent acts like a YouTube content assistant, capable of producing:

Creative & high-quality video ideas

Complete 2-minute scripts

SEO keyword-rich descriptions

Thumbnail suggestions

Summaries of long content

The agent uses:

Gemini-based LLM

MCP server for tools

Memory components

A multi-step reasoning pipeline

This project demonstrates how to build a real-world AI agent with practical value.

🧠 Features
✔️ Idea Generator

Produces unique, creative YouTube video ideas based on any topic.

✔️ Script Writer

Creates a full 1–2 minute video script including:

Hook

Body narration

CTA

Voice-over tone

✔️ SEO Description Generator

Generates an optimized YouTube description with:

Keywords

Tags

Hashtags

Title suggestions

✔️ Summarizer

Summarizes long scripts or research into a short creator-friendly summary.

✔️ Multi-Agent-Style Reasoning

Uses MCP tool functions + LLM to chain multiple steps of content creation.

✔️ Memory Support

The agent remembers:

Topic preference

Style

Voice tone

🏗️ Architecture
User Query  
      ↓  
YouTube Agent  
      ↓  
MCP Tools (Idea Tool, Script Tool, Summary Tool)  
      ↓  
LLM (Gemini / Other)  
      ↓  
Final Output

📂 Repository Structure
├── Notebook.ipynb            # Full Kaggle notebook (run-ready)
├── README.md                 # Project documentation
├── requirements.txt          # Libraries used in notebook
├── agent_config.json         # Optional agent structure
└── .gitignore                # Clean repo by ignoring junk files

⚙️ Tech Stack
Component	Used For
Python	Core implementation
MCP (Model Context Protocol)	Agent tools
LLM (Gemini / OpenAI compatible)	Generating ideas, scripts, descriptions
Memory system	Session context
TQDM / JSON / Requests	Helper utilities
🚀 How to Run the Notebook
1. Install Dependencies
pip install -q -U pip
pip install "numpy<2" mcp python-dotenv requests tqdm

2. Add Your API Key

In the notebook, update:

api_key = "YOUR_API_KEY"

3. Run All Cells

The notebook is structured into:

Setup

MCP Tool definitions

Agent construction

Demo outputs

🎥 Sample Outputs
Video Ideas

“5 AI Tools to Grow Your YouTube Channel Fast”

“YouTube Automation Explained in 2 Minutes”

Script Example

Hook

Body narration

Scene breakdown

CTA

SEO Descriptions

Keywords

Tags

Hashtags








