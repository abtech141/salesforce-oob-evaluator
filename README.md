# Salesforce OOB Evaluator — Claude Skill

A Claude skill that evaluates any Salesforce business requirement 
strictly against Out-of-the-Box (OOB) native features.

## What it does
- Scores each relevant Salesforce feature (0–100% fitment)
- Estimates configuration effort (Low / Medium / High)
- Maps required license and Salesforce edition
- Identifies the best 1–2 native options
- Summarizes OOB gaps clearly — no custom code suggestions

## Covers (Spring '26+)
Agentforce · CRM Analytics · Collaborative Forecasts · 
Revenue Cloud · Einstein AI · Reports & Dashboards · 
Service Cloud · Sales Cloud · Platform features

## How to install
Download `salesforce-oob-evaluator.skill` and upload it 
in Claude.ai → Settings → Skills.

## Rules enforced
❌ No Custom Objects  
❌ No Apex / LWC  
❌ No Custom Flows  
✅ OOB only
