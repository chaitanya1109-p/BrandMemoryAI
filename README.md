# BrandMemory AI

BrandMemory AI is a privacy-focused AI content strategy agent that learns from historical content performance and generates evidence-based recommendations for future content.

## Problem

Brands often have large amounts of historical content data, but it can be difficult to identify which topics, platforms, and content patterns actually perform well.

## Solution

BrandMemory AI analyzes historical content performance and builds a "Brand Memory" from the data.

It identifies:

- Topic performance
- Platform performance
- Engagement patterns
- Conversion patterns
- High-impact content
- Successful content patterns

The system then uses a locally hosted Gemma model through LM Studio to generate an AI-powered content strategy.

## Architecture

CSV Dataset
↓
Pandas Data Analysis
↓
Brand Memory
↓
Local Gemma Model through LM Studio
↓
AI Content Strategy

## Key Features

- Historical content performance analysis
- Topic and platform analysis
- Conversion insights
- Successful content pattern detection
- AI-generated content recommendations
- Local AI processing using LM Studio
- Privacy-focused architecture

## Technologies

- Python
- Streamlit
- Pandas
- LM Studio
- Gemma
- OpenAI-compatible API

## How to Run

Install the required packages:

```bash
pip install -r requirements.txt