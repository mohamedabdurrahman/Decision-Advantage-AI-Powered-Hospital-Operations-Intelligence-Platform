I designed and built this end-to-end, solo: an AI-powered operations intelligence platform that helps hospital teams spot pressure (ED surge, bed shortages, discharge delays) before it becomes a crisis, and act on it with AI-generated, evidence-backed recommendations.

The problem: hospitals often only detect operational pressure once it's severe, decisions are scattered across roles, and there's little shared visibility — a lag known as decision latency, which drives overcrowding and corridor care.

What I built: IPCI (Integrated Predictive Care Intelligence), a four-layer architecture — data, predictive insight, decision support, governance — combining synthetic operational modelling, a FastAPI + Pydantic backend, an AI reasoning layer (OpenAI GPT + Codex), and a React/TypeScript frontend with role-based views (ED Nurse to Operations Director), deployed on Render.

Highlights:
- Flow Score and pressure indicators (ED, DTOC, LOS, boarding), with a Mixed Pressure scenario engine modelling compounding stress
- AI-driven Priority Action Engine: recommends actions with confidence scores and evidence, with mandatory human review — not a black box
- Full explainability and audit trail (signals, assumptions, uncertainty, decision history), aligned with GDPR / EU AI Act principles
- Executive-ready AI-generated leadership briefings

Tech: Python, FastAPI, Pydantic, OpenAI (GPT + Codex), React/TypeScript, Render, GitHub

Why it matters: reducing decision latency is one of the highest-leverage levers in hospital operations. This is a working demonstration of responsible, human-in-the-loop AI addressing it — end-to-end, from architecture through governance to a deployed, usable interface.

Built solo during OpenAI Build Week. https://devpost.com/software/decision-advantage-ipci-operations-intelligence-co-pilot

Platform: https://operah-care.lovable.app
