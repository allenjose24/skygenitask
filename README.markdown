# Skygeni Task: Data Analysis Project

This repository contains a Python-based data analysis project that answers four questions about client industries, subscription renewals, inflation rates, and payment methods using Jupyter notebooks. It includes datasets, code, and visualizations to explore Finance Lending and Blockchain clients, industry renewal rates, inflation impacts, and payment trends.

## Project Structure

- `data/`: Datasets (`financial_information.csv`, `industry_client_details.csv`, `payment_information.csv`, `subscription_information.csv`).
- `notebooks/`: Jupyter notebook (`skygenitask.ipynb`) with analysis and visualizations.
- `results/figures/`: Visualization outputs (`q1_plot.png`, `q2_plot.png`, `q3_plot.png`, `q4_plot.png`).
- `docs/`: Documentation (`project_plan.md`).
- `.gitignore`: Ignores temporary files (e.g., `.ipynb_checkpoints/`, `__pycache__/`).
- `requirements.txt`: Python dependencies.
- `setup.sh`: Setup script for environment.
- `LICENSE`: MIT License.

## Questions Answered

1. How many Finance Lending and Blockchain clients does the organization have?
2. Which industry has the highest renewal rate?
3. What is the average inflation rate at the time of renewal for subscriptions that were renewed?
4. What is the median yearly payment for all payment methods?

## Setup Instructions

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/skygenitask.git
   cd skygenitask
   ```

2. **Set up the environment**:

   ```bash
   bash setup.sh
   ```

   Alternatively, manually install dependencies:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Run the notebook**:

   ```bash
   jupyter notebook notebooks/skygenitask.ipynb
   ```

4. **View results**:

   - Visualizations are saved in `results/figures/`.
   - Outputs are printed in the notebook (e.g., renewal rates, median payments).

## Dependencies

Listed in `requirements.txt`:

- pandas
- matplotlib
- seaborn
- jupyter

Install them via:

```bash
pip install -r requirements.txt
```

## Datasets

The datasets in `data/` are:

- `financial_information.csv`: Financial metrics (e.g., inflation rates).
- `industry_client_details.csv`: Client industry and company details.
- `payment_information.csv`: Payment records (e.g., amount, method).
- `subscription_information.csv`: Subscription details (e.g., renewal status).

*Note*: If datasets are large or sensitive, they may be excluded (check `.gitignore`). In that case, download them from \[insert link, if applicable\] and place them in `data/`.

## Results

Key findings (see `notebooks/skygenitask.ipynb` for details):

- Visualizations for each question are in `results/figures/` (`q1_plot.png` to `q4_plot.png`).
- Example output: Gaming has the highest renewal rate at 72.73%.

## Documentation

- `docs/project_plan.md`: Project goals, methodology, and interpretation of results.
- Additional details are in the notebook’s comments and outputs.

## Contact

For questions, contact me at allenjose2110@gmail.com or open an issue on GitHub.

---

Built with Python, pandas, matplotlib, and seaborn. Happy analyzing!
