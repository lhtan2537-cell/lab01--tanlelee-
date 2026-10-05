# Smart Virtual Assistant

A rule-based assistant for student queries.

## Prerequisites
- Python >= 3.10
- Git

## Setup
git clone https://github.com/lhtan2537-cell/lab01--tanlelee-.git
cd lab01--tanlelee-
python -m venv .venv
source .venv/Scripts/activate
pip install -r requirements.txt
pip install -e .

## Run
python -m assistant "where is the IT helpdesk?"

## Test
pytest -q
