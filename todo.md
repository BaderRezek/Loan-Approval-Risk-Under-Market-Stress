**Step 1:**
- [ ] Download and clean LendingClub data
  - [ ] pick variables
  - [ ] define default target
- [ ] Set up pipeline to pull market data from FRED.

**Step 2:**
- [ ] Train baseline model (logistic regression).
- [ ] Train gradient boosting model.
- [ ] Validate on holdout data.
- [ ] Build stress-scenario code.

**Step 3:**
- [ ] Integrate macro variables into model (ARIMAX or gradient boosting with macro features).
- [ ] Document data merges.

**Step 4:**
- [ ] Apply SHAP to baseline and boosted models
  - [ ] produce global + local plots.
- [ ] Partner finishes scenario simulation engine.

**Step 5:**
- [ ] Build simple Streamlit app
  - [ ] user inputs loan features + market conditions → model outputs default probability + SHAP explanation.
- [ ] Add “stress sliders.”

**Step 6:**
- [ ] Write a “model risk report”: 
  - [ ] methods, 
  - [ ] performance, 
  - [ ] feature stability, 
  - [ ] stress results, 
  - [ ] limitations

**Step 7:**
- [ ] Polish dashboard
- [ ] finalize documentation
- [ ] prepare presentation deck and resume bullets
