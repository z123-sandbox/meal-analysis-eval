# AGENTS.md

## Project
Meal analysis eval suite for a health-tech AI system built on OpenAI APIs.

## Stack
- Python 3.11
- openai SDK (latest)
- pytest

## Models
- Inference: gpt-5.4-mini (multimodal)
- Moderation: omni-moderation-latest

## Rules
- Output must never contain medical advice or dietary recommendations
- All nutritional output must conform to the schema in /schemas/nutrition_output.json
- Tests must be runnable with: pytest tests/

## Test images
- Located in /images/
- Use real food photos only
