# LLM Alignment: Full Fine-Tuning, Q-LoRA, and DPO

## Project Overview

This project is a comparative study of various Large Language Model (LLM) alignment strategies on code generation and behavioral safety tasks. We investigate and benchmark the following alignment methods:

- **Full Fine-Tuning:** Classic method of updating all model parameters.
- **Parameter-Efficient Fine-Tuning (Q-LoRA):** Fine-tuning select/adapted model parameters using Q-LoRA, which is more resource-efficient.
- **Direct Preference Optimization (DPO):** Preference-based tuning aligning the model directly with human preferences.

We apply these techniques to LLMs and evaluate their effectiveness in both code generation and safety-critical tasks, providing quantitative and qualitative insights into their respective trade-offs.

---

## Repository Structure

- `notebooks/`
  - `01_data_preparation.ipynb`: Dataset loading, preprocessing, and full fine-tuning workflow   
    [Open in Colab](https://colab.research.google.com/drive/1OvQ6IkqJ1VamfIoiL5zBTX-OYDzKYvaa?usp=sharing)
  - `02_peft_q_lora.ipynb`: Q-LoRA PEFT workflow  
    [Open in Colab](https://colab.research.google.com/drive/1xqnLW1X3PKth9CxNLrJMTTvoE5s3ponc?usp=sharing)
  - `03_dpo_training.ipynb`: DPO (Direct Preference Optimization) workflow, results analysis and comparison.                       
    [Open in Colab](https://colab.research.google.com/drive/164o3-z7P89PJ2bQzvf6XHjIDuBItWMf8?usp=sharing)

---

## Quick Start

1. **Clone the Repo**
    ```bash
    git clone https://github.com/MazenBassem/NLP-LLM-Alignment-FineTuning-PEFT-DPO.git
    cd NLP-LLM-Alignment-FineTuning-PEFT-DPO
    ```

2. **Run on Colab**
    - Open each notebook using the “[Open in Colab](#)” links above.
    - Make sure to follow the instructions in each notebook to set up dependencies and environment.

3. **Data Preparation**
    - See `01_data_preparation.ipynb`.
    - Download/prepare datasets as instructed.

4. **Training & Evaluation**
    - Sequentially execute the notebooks for each method and compare results in `05_evaluation.ipynb`.

---

## Results

<!-- Fill this with summaries of your experiments -->

**Summary Table:**

| Method              | Task             | Metric (e.g. F1, BLEU, Accuracy) | Result  |
|---------------------|------------------|----------------------------------|---------|
| Full Fine-Tuning    | Code Generation  | [Metric Name]                    | [Value] |
| Q-LoRA              | Code Generation  | [Metric Name]                    | [Value] |
| DPO                 | Code Generation  | [Metric Name]                    | [Value] |
| ...                 | ...              | ...                              | ...     |

- Add plots or figures if available (insert images/plots here).

**Key Findings:**

- [Briefly summarize main results, findings, or insights. E.g.: “Q-LoRA achieves 95% of the performance of full fine-tuning with only 10% of the parameter update cost...”]
- [Highlight safety/behavioural metrics results, if any.]

---

## Acknowledgments

This project draws upon ideas, code, and resources from the following:

- [HuggingFace Transformers](https://huggingface.co/transformers/)
- [PEFT: Parameter-Efficient Fine-tuning Library](https://github.com/huggingface/peft)
- [trlX: Open-source RLHF for Language Models](https://github.com/carperai/trlx)
- Research papers and open-source communities working on LLM fine-tuning and alignment.

Special thanks to the following people and sources for inspiration, support, or helpful discussions:

- [List names, papers, mentors, or classmates—edit as needed]

---
