This repository contains the code and notebooks accompanying the article:

> **Reduced-order model for parametrized Optimal Transport
problems**
> Elise Bonnet-Weill, Virginie Ehrlacher, Luca Nenna
>
## Contents

All files for the article are in the [`2026_ROM`](2026_ROM) folder:

| File | Description |
|------|-------------|
| [`Model_order_reduction_for_Optimal_Transport_Tutorial.ipynb`](2026_ROM/Model_order_reduction_for_Optimal_Transport_Tutorial.ipynb) | **Start here.** A tutorial that walks through the method step by step and applies it to color transfer between images. |
| [`Time_precision_comparison_and_error_estimation.ipynb`](2026_ROM/Time_precision_comparison_and_error_estimation.ipynb) | All other numerical experiments from the article: computation time and precision comparisons, and error estimation. |
| [`Photos/`](2026_ROM/Photos) | Images used in the color transfer examples. |

## Usage

1. Clone or download the repository:
   ```bash
   git clone https://github.com/elisebonnetweill/Code.git
   ```
   or download it as a zip: [Code-main.zip](https://github.com/elisebonnetweill/Code/archive/refs/heads/main.zip)
2. Open the notebooks from the `2026_ROM` folder (with Jupyter, JupyterLab, VS Code or Google Colab) so the `Photos/` folder is found.
3. Start with the tutorial notebook, then run the experiments notebook to reproduce the results of the article.
