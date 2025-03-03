---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Skills
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: skills
  count: 8
  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
  - name: Programming languages
    tag: Programming languages
  - name: ML and DL Frameworks
    tag: ML and DL Frameworks
  - name: Statistical Analysis
    tag: Statistical Analysis
  - name: Visualisations and Dash-boarding
    tag: Visualisations and Dash-boarding
  - name: MLOps Tools
    tag: MLOps Tools
  - name: Machine Learning
    tag: Machine Learning
  - name: Data Science and Engineering
    tag: Data Science and Engineering
  - name: Software Development and Tools
    tag: Software Development and Tools

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  # view: masonry
  view: Compact

  # For Showcase view, flip alternate rows?
  flip_alt_rows: true
---

<!-- Programming languages
Python, Java, MATLAB
ML and DL Frameworks
TensorFlow, Keras, PyTorch, scikit-learn
Visualisations & Dash-boarding
Plotly, Dash, Streamlit, seaborn, matplotlib
MLOps Tools
MLflow, AWS SageMaker, CI/CD Pipelines for ML (Docker, GitHub Actions)
Statistical Analysis
A/B testing, hypothesis testing, regression analysis
Machine Learning & AI
Supervised & Unsupervised Learning algorithms, Explainability (SHAP, LIME), Fairness/Bias, Adversarial Robustness, AI Risk Assessment & Compliance
Data Science & Engineering
Data Preprocessing (Pandas, NumPy), SQL Databases, Feature Engineering
Software Development & Tools
Bash, Rest APIs, Celery, Git, Agile Methodologies  -->