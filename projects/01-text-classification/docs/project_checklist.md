# Text Classification Project Checklist

## Phase 1: Data Setup
- [ ] Select dataset with at least 10,000 labeled text examples
- [ ] Load data and verify at least 3 distinct categories
- [ ] Clean text: remove special characters, standardize case, handle missing values
- [ ] Create 60/20/20 train/validation/test split
- [ ] Verify data quality: no empty strings, consistent labels

## Phase 2: Basic Model (Classical)
- [ ] Create TF-IDF vectorizer with max 10,000 features
- [ ] Train LogisticRegression classifier
- [ ] Calculate accuracy, precision, recall on test set
- [ ] Document baseline metrics in progress.md
- [ ] Save vectorizer and model with version number

## Phase 3: Model Improvements
- [ ] Train RandomForest with 100 estimators
- [ ] Create voting ensemble of LogReg + RandomForest
- [ ] Fine-tune small BERT model (bert-base-uncased)
- [ ] Generate comparison table of all model metrics
- [ ] Select best model based on accuracy/speed trade-off

## Phase 4: Model Understanding
- [ ] Generate SHAP values for top 10 features
- [ ] Implement LIME explanations for individual predictions
- [ ] Create confusion matrix visualization
- [ ] Plot feature importance graph
- [ ] Document interpretation methods in README

## Phase 5: Production Ready
- [ ] Create Flask API with /predict endpoint
- [ ] Add error handling for malformed inputs
- [ ] Write tests for each endpoint (>80% coverage)
- [ ] Verify response time <100ms per prediction
- [ ] Create API documentation with example calls

## Success Metrics
- [ ] Overall accuracy >85% on test set
- [ ] Per-category F1 scores >0.80
- [ ] API response time <100ms
- [ ] All tests passing
- [ ] Documentation complete and accurate

## Project Organization
- [ ] Organized code in src/ with clear function names
- [ ] Data versioned and stored in data/
- [ ] Exploration notebooks in notebooks/
- [ ] Updated README with setup and usage instructions
- [ ] Complete requirements.txt with version numbers
- [ ] All code following PEP 8 style guide

Each item can be clearly marked as done/not done, and success can be measured objectively.