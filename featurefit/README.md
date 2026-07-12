# FeatureFit — AI-Powered Feature Prioritization

A Streamlit app that uses GPT-4 to analyze and prioritize product features using RICE scoring, MoSCoW prioritization, SWOT analysis, and roadmap generation.

## Quick Start

```bash
pip install -r requirements.txt
streamlit run featurefit.py
```

## Docker

```bash
docker build -t featurefit .
docker run -p 8501:8501 -e OPENAI_API_KEY=your_key featurefit
```

## Deploy to Coolify

1. Push this repo to GitHub
2. In Coolify, create a new app from this repo
3. Set `OPENAI_API_KEY` as an environment variable
4. Port: 8501
5. Deploy

## What It Does

- Takes a feature name, industry, business goal, and context
- Generates RICE scores (Reach, Impact, Confidence, Effort)
- Assigns MoSCoW priority with justification
- Provides SWOT analysis
- Suggests MVP roadmap with phases and timelines
- Identifies risks and confidence improvement areas
- Asks clarifying questions to refine analysis

## Use Case

Perfect for:
- Product teams doing quarterly planning
- Founders validating MVP features
- PMs presenting prioritization to stakeholders

## License

MIT
