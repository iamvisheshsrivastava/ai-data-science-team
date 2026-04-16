# AI Data Science Team

This repository combines the `ai_data_science_team` Python package with several apps and examples for AI-assisted data science workflows. The main showcase is AI Pipeline Studio, a Streamlit app for building reproducible data workflows through a visual interface.

## What is included

- `ai_data_science_team/`: library code for agents, tools, and workflow components
- `apps/`: application entrypoints, including AI Pipeline Studio and related demos
- `examples/`: runnable examples for common data science tasks
- `data/`: sample data and project assets
- `img/`: screenshots and visual assets

## Core capabilities

- data loading, inspection, and wrangling
- exploratory data analysis and visualization
- feature engineering and modeling workflows
- SQL- and dataframe-oriented assistants
- reproducible app-driven experimentation with Streamlit

## Quickstart

### Requirements

- Python 3.10 or newer

### Install

```bash
git clone https://github.com/iamvisheshsrivastava/ai-data-science-team.git
cd ai-data-science-team
pip install -e .
```

### Run AI Pipeline Studio

```bash
streamlit run apps/ai-pipeline-studio-app/app.py
```

## Repository layout

```text
ai-data-science-team/
|-- ai_data_science_team/
|-- apps/
|-- examples/
|-- data/
|-- img/
|-- README.md
|-- requirements.txt
`-- setup.py
```

## Notes

- App-specific documentation lives alongside the individual apps in `apps/`.
- `examples/` is a good starting point if you want to explore the code before using the UI.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
