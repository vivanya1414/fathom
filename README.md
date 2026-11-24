# fathom
A no-code AI research assistant built using Dify, GPT-5 and Tavily Search.
# ResearchMate AI – Intelligent Research Assistant

An AI-powered research assistant built using Dify, GPT-5 and Tavily Search. ResearchMate AI helps users explore different topics and generate structured research reports using web search results.

## Overview

ResearchMate AI is a no-code AI agent designed to simplify the research process. It accepts a research topic, searches for relevant information and generates an organised research report.

## Features

- AI-powered research assistance
- Web search integration using Tavily
- GPT-5-powered report generation
- Structured research outputs
- Source references and URLs
- Supports multiple research domains

## Technology Stack

- **Dify:** AI workflow development
- **GPT-5:** Language model for research analysis and report generation
- **Tavily Search:** Web search integration

## Workflow Architecture

User Input → Tavily Search → GPT-5 → Generated Research Report

## Report Structure

1. Research Overview
2. Research Objectives
3. Key Findings
4. Evidence and Analysis
5. Advantages and Challenges
6. Conclusion
7. Sources and References

## How It Works

1. The user enters a research topic.
2. Tavily Search retrieves relevant web information.
3. GPT-5 analyses the available information.
4. ResearchMate AI generates a structured research report.
5. The final report is displayed to the user.

## Project Objective

To build an accessible AI-powered research assistant that simplifies information discovery, analysis and report generation through a no-code workflow.

## Limitations

- Report quality depends on the relevance and reliability of retrieved sources.
- AI-generated information should be independently verified.
- Insufficient search results may affect research completeness.

## Future Improvements

- Improved source verification
- PDF report export
- Research history
- Enhanced citation handling
- Multi-source research comparison

## Author

Developed as a personal AI and Data Science portfolio project.

## System Architecture

```mermaid
flowchart TD
    A[User Input: Research Topic]
    B[Tavily Search]
    C[GPT-5: Research Analysis]
    D[Generated Research Report]

    A --> B
    B --> C
    C --> D



This represents the actual workflow:

<box border radius="lg" padding={3} gap={2} align="center">
  <box background="surface-secondary" radius="md" padding={2} width="75%" align="center">User Input</box>
  <icon name="arrow-down"/>
  <box background="surface-secondary" radius="md" padding={2} width="75%" align="center">Tavily Search</box>
  <icon name="arrow-down"/>
  <box background="surface-secondary" radius="md" padding={2} width="75%" align="center">GPT-5 Analysis</box>
  <icon name="arrow-down"/>
  <box background="rgba(34,197,94,0.10)" radius="md" padding={2} width="75%" align="center">Research Report</box>
</box>

try fathom:https://udify.app/chat/zT4jlWeHeqHHwjxO
