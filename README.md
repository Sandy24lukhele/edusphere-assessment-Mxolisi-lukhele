# edusphere-assessment-Mxolisi-lukhele
EduSphere Micro-Learning Orchestrator using n8n, Supabase, and AI Model
# EduSphere Mini Technical Assessment

## Overview
This project is a micro-learning orchestration system built using n8n, Supabase, and an AI model.

## Features
- AI-powered student answer evaluation
- Score generation (0–10)
- Multilingual feedback (isiZulu supported)
- Conditional routing (Approved / Flagged)
- Data storage in Supabase

## Workflow
1. Webhook receives student submission
2. Data is cleaned using Set node
3. AI evaluates answer
4. Output is parsed
5. IF node routes based on score
6. Data is stored in Supabase

## Demo Video
Loom Video:
https://drive.google.com/file/d/12W4c9XGdw6bUxuoIrs9cgk0WOjzgFqaA/view?usp=sharing

## Tools Used
- n8n
- Supabase
- OpenAI / LLM API
- Postman

## Author
Mxolisi Lukhele
