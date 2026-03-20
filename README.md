# LLM-VLM Framework

A comprehensive framework for Large Language Model (LLM) and Vision-Language Model (VLM) training.

## Features

- **LLM Training Pipeline**: Pre-training, SFT, RLHF (DPO, PPO, GRPO)
- **VLM Training**: Vision encoder integration, multimodal fusion
- **Data Collection**: WeChat article crawler, dataset builder
- **Deployment**: API server, Gradio UI

## Project Structure

```
.
├── config/              # Configuration files
├── configs/             # Training configurations
│   ├── llm/            # LLM training configs
│   └── vlm/            # VLM training configs
├── docs/               # Documentation
├── examples/           # Usage examples
├── runs/               # Training runs
├── scripts/            # Shell scripts
├── src/                # Source code
│   ├── common/         # Shared utilities
│   ├── data_collection/# Data collection tools
│   ├── llm_training/   # LLM training modules
│   └── vlm_training/   # VLM training modules
├── tests/              # Test files
├── requirements.txt    # Python dependencies
└── setup.py           # Package setup
```

## Quick Start

```bash
# Install dependencies
pip install -r requirements.txt

# Run training demo
python demo_training.py

# Run pipeline
bash scripts/llm/pipeline.sh
```

## License

MIT
