# Goldilocks Search 🪐

**A NASA Exoplanet Archive Analysis in Search of Earth 2.0**

Welcome to **Goldilocks Search**, a data-driven journey through the cosmos to identify potentially habitable exoplanets. Using the latest data from the NASA Exoplanet Archive, this project filters through thousands of confirmed planets to find those that might just be "just right" for life as we know it.

This project was created as part of the **Codédex Data Analysis Monthly Challenge**.

## 🚀 Key Features

- **Interactive Scrollytelling Narrative**: Experience the data discovery process through a guided, step-by-step narrative that explains the science behind the search.
- **Exoplanet Basics**: Includes specialized sections ("What is an Exoplanet?", "The Goldilocks Zone") to make the science accessible to everyone.
- **3D Visualizations**: Explore the finalists with interactive 3D spinning globes, bringing the data to life.
- **Robust Data Consolidation**: Implements a rigorous methodology to consolidate multiple measurement sources, ensuring the most accurate data is used for analysis.
- **Plain Language Explanations**: Technical jargon is broken down into simple terms, making complex astrophysical concepts easy to understand.
- **Direct NASA Archive Integration**: Analyses are based on real-world data directly from the NASA Exoplanet Archive.

## 🔍 Methodology: The Funnel

The search for Earth 2.0 follows a strict "funnel" approach to filter candidates:

1.  **Confirmed Exoplanets**: Start with the full NASA archive.
2.  **Radius Filter**: Select planets with a rocky composition (0.5 - 1.6 Earth radii).
3.  **Temperature Filter**: Identify planets within the "Goldilocks Zone" (equilibrium temperature permitting liquid water).
4.  **Star Type Filter**: Focus on stable, long-lived stars (F, G, K spectral types) suitable for evolution.

## 🛠️ Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or Lab

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/goldilocks-search.git
    cd goldilocks-search
    ```

2.  **Set up a Virtual Environment:**
    - **Windows:**

      ```bash
      python -m venv .venv
      .venv\Scripts\activate
      ```

    - **MacOS / Linux:**
      ```bash
      python3 -m venv .venv
      source .venv/bin/activate
      ```

3.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the Notebook:**
    ```bash
    jupyter notebook exoplanets-goldilocks-search.ipynb
    ```

## 📊 Visualizations

The notebook includes dynamic Plotly visualizations:

- **Funnel Charts**: Tracking the candidate pool size at each filter stage.
- **Scatter Plots**: Analyzing the relationship between planet size and orbital period.
- **3D Globes**: Visualizing the final Earth 2.0 candidates.

## 🙏 Acknowledgments

- **NASA Exoplanet Archive**: For providing the incredible open-access data.
- **Codédex**: For the monthly challenge inspiration.
- **Alan Geirnaert**: Author and Analyst.

---

_Note: This analysis is for educational purposes and is based on data available as of February 2026._
