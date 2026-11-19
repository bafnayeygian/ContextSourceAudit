# ContextSourceAudit

Audit assembled LLM context packs for source diversity, duplicate passages, missing citations, token concentration, and oversized evidence blocks.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/ContextSourceAudit.git
cd ContextSourceAudit
python -m pip install .
```

## Usage

```bash
context-source-audit --help
```

## Development

```bash
python -m unittest discover -s tests -v
```
