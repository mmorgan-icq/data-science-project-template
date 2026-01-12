# data-science-project-template

# Project Title

> One-sentence description of the model and the business problem it solves.

---

## 1. Points of Contact

| Role | Name | Email / Slack |
|-----|------|---------------|
| Product Owner |  |  |
| Tech Lead |  |  |
| ML Owner |  |  |
| Data Owner |  |  |
| On-Call / Support |  |  |

---

## 2. Business Objective

### Problem Statement
- What decision or prediction does this model support?
- Who consumes the output?

### Success Metrics
- Business KPIs tied to model outcomes
- Examples: revenue lift, cost reduction, error reduction

### Constraints
- Latency requirements
- Cost constraints
- Regulatory or compliance requirements

---

## 3. Data Sources

### Input Data
| Source | Description | Location | Refresh Cadence |
|------|-------------|----------|-----------------|
|  |  |  |  |

### Target Variable
- Definition
- Labeling method
- Known noise or bias

### Feature Engineering
- Core features used
- Transformations and encodings
- Feature store usage (if applicable)

### Data Validation
- Schema checks
- Missing value handling
- Outlier detection

### Privacy & Security
- PII presence
- Masking / anonymization strategy
- Access controls

---

## 4. Repo Structure

```text
├── data/
│   ├── raw/
│   ├── processed/
│   └── features/
├── notebooks/
├── src/
│   ├── data/
│   ├── features/
│   ├── models/
│   ├── training/
│   ├── inference/
│   └── utils/
├── tests/
├── configs/
├── artifacts/
├── scripts/
└── README.md
