# Quick Reference: Text Classification Project

## Key Locations
- Project checklist: `docs/project_checklist.md`
- Daily log: `notes/progress.md`
- Code: `src/`
- Data: `data/`
- Notebooks: `notebooks/`

## Essential PyCharm Commands
- Open commit window: Cmd + K
- Push to GitHub: Cmd + Shift + K
- Find file: Cmd + Shift + O
- Toggle file tree: Cmd + 1

## Git Actions
```bash
# Check status
git status

# Create new branch
git checkout -b feature-name

# Update from main
git pull origin main
```

## Virtual Environment
- PyCharm manages this automatically
- Requirements in requirements.txt

## Project Structure
```
src/
    data_processing.py    # Data loading & cleaning
    model.py             # Model implementation
    train.py            # Training logic
    evaluate.py         # Evaluation code
    app.py             # Flask API
```

## Key Dependencies
- pandas: Data handling
- scikit-learn: Classical ML
- torch: Deep learning
- transformers: BERT
- flask: API

## When Stuck
1. Check project checklist
2. Review error message
3. Ask for help if stuck >30 min