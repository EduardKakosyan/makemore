# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a follow-along implementation of Andrej Karpathy's makemore series, which teaches neural networks and language modeling from scratch. The project focuses on building character-level language models using PyTorch.

## Development Setup

This project uses Python and will primarily work with Jupyter notebooks for experimentation and Python scripts for implementations.

### Environment Setup
- Create a virtual environment: `python -m venv venv`
- Activate environment: `source venv/bin/activate` (macOS/Linux) or `venv\Scripts\activate` (Windows)
- Install dependencies when available: `pip install -r requirements.txt`

### Common Commands
- Run Python scripts: `python script_name.py`
- Launch Jupyter notebooks: `jupyter notebook` or `jupyter lab`
- Install packages: `pip install package_name`

## Code Architecture

The project will likely follow this structure as it develops:
- Jupyter notebooks for experimentation and tutorials
- Python modules for reusable model implementations
- Data processing utilities for text datasets
- Training scripts for different model architectures

## Development Notes

- Follow the makemore series progression: start with simple bigram models, then move to more complex architectures
- Implement models from scratch to understand the underlying mechanics
- Focus on character-level language modeling initially
- Use PyTorch as the primary deep learning framework
- Maintain clean separation between experimental notebooks and production code