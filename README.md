# 🦦 otter-ml

> Talk to your data, get ML models.

The ML framework that speaks engineer. No PhD required.

## Usage

```bash
npx otter-ml
```

That's it. Otter handles the rest.

## What it does

Connect your database or CSV → tell Otter what you want to predict → get a trained model.

```
🦦 Hey! I'm Otter. What do you want to work with today?

> I have a CSV with customer data, want to predict who will cancel

🦦 Let's load it. Drop the file path or paste the URL.

> ./customers.csv

🦦 Loaded 45,231 rows, 18 columns.
   I see a "churned" column — is that what you want to predict?

> yes

🦦 Training... ████████░░ 82% — XGBoost looking good
   Done! Your model is right 87% of the time.
```

## Supported AI providers

Otter needs an AI provider to understand your data. Pick one:

| Provider | Cost | Setup |
|----------|------|-------|
| Ollama | Free | Install Ollama locally |
| Anthropic | ~$0.01/session | API key |
| OpenAI | ~$0.01/session | API key |
| OpenRouter | Flexible | API key |

## Source

Python core: [otter-ml/otter](https://github.com/otter-ml/otter)
