# IT Helpdesk CSV SLA Lab

CSV helpdesk management lab for synthetic tickets, SLA calculation, open queue summary, and productivity report.

> Educational project inspired by EETEPA Vilhena Alves. It is not an official institutional system and does not use real student data.

## Overview

**Curricular code:** I-11  
**Course:** Technical Computing  
**Discipline:** Applied IT Management  
**Difficulty:** Introductory

This repository is a runnable Python MVP for portfolio and classroom practice. The default command uses only safe sample data committed to `data/sample/`.

## Concepts Practiced

- CSV CRUD
- datetime
- status reports
- SLA
- IT service management

## Repository Structure

```text
data/
  sample/       # safe synthetic samples
  raw/          # optional external files, ignored except .gitkeep
  processed/    # generated outputs, ignored except .gitkeep
notebooks/
  01_exploracao.ipynb
scripts/
  download_data.py
src/
  main.py
charts/
reports/
```

## Quick Start

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python -m src.main --sample
```

Linux/macOS activation:

```bash
source .venv/bin/activate
```

## Safe Operations

- The CI workflow never scans live networks, scrapes sites, runs speed tests, sends packets, or calls external APIs.
- Real-world data collection, when applicable, must be performed only in authorized lab environments.
- Generated outputs are written to `data/processed/`, `charts/`, or `reports/`.

---

# IT Helpdesk CSV SLA Lab

CSV helpdesk management lab for synthetic tickets, SLA calculation, open queue summary, and productivity report.

> Projeto educacional inspirado na EETEPA Vilhena Alves. Nao e sistema oficial institucional e nao usa dados reais de estudantes.

## Visao Geral

**Codigo curricular:** I-11  
**Curso:** Tecnico em Informatica  
**Disciplina:** Gestao Aplicada a Informatica  
**Dificuldade:** Introdutorio

Este repositorio e um MVP Python executavel para portfolio e pratica em sala. O comando padrao usa apenas dados de amostra seguros em `data/sample/`.

## Conceitos Praticados

- CSV CRUD
- datetime
- status reports
- SLA
- IT service management

## Como Rodar

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python -m src.main --sample
```

## Operacao Segura

- O CI nunca varre redes reais, faz scraping, executa speed tests, envia pacotes ou chama APIs externas.
- Coleta real de dados, quando aplicavel, deve ocorrer apenas em ambientes de laboratorio autorizados.
- Saidas geradas ficam em `data/processed/`, `charts/` ou `reports/`.

## License

MIT. See [LICENSE](LICENSE).
