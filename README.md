
---

# FinLens AI helps assess credit risk for small businesses

A fresh look at finance tools begins here - FinLens AI works like a specialist reader trained just for business money matters. Instead of general knowledge, it focuses only on small and medium companies. Picture something that reads financial details deeply, then builds clear reports about lending risks. This system learns patterns tied to company stability. It shapes insights into organized formats lenders can follow easily. Credit decisions gain support through focused analysis, not guesswork. The model does not wander beyond its purpose. Every output links directly to enterprise financial behavior. Precision comes from narrow training, not broad data.

A full step-by-step tuning process lives here, built inside a Jupyter Notebook. It runs straight on Google Colab without extra configuration. The whole workflow is included from start to finish.

---

## Project Overview

Out of nowhere, numbers like cash flow, debt levels, and earnings come into play when small business loans get reviewed. A person trained in finance usually sorts through these details. With FinLens AI, that thinking process gets mirrored - step by step, without skipping corners. Instead of relying only on human judgment, the system follows patterns similar to an experienced evaluator. It pieces together clues much like someone who has seen hundreds of balance sheets. Not magic, just logic shaped by real-world examples. The result? An automated take on what once demanded hours of manual review.

* Interpreting financial ratios
* Classifying credit risk (Low / Moderate / High)
* Providing structured explanations
* Highlighting key financial warning signals

A single model shows its ability to shift from broad tasks to focused finance help through smart tweaks - no full rebuild needed. Small adjustments unlock big changes, turning wide knowledge into sharp tools. Efficiency guides the process, making upgrades lean yet powerful. Training stays light but effective, shaping responses without heavy lifting.

---

## Repository Structure

The notebook includes:

* Synthetic dataset generation
* Data preprocessing and formatting
* Model loading and PEFT configuration
* Fine-tuning pipeline
* Risk distribution visualization
* Inference and chatbot deployment (Gradio)

---

## Demo Video: https://youtu.be/s6FvNc7l-hc

## Dataset

The dataset consists of 1,200 synthetic SME financial examples.

Each example includes:

* Revenue
* Debt
* Assets
* Current Ratio
* Debt-to-Asset Ratio
* Net Margin
* Risk Level: Low, Medium, or High
* Structured financial explanation

Starting with how cash moves, risk tags come from set rules that score money health. Liquidity levels steer part of the call, while debt load shapes another piece. Profit patterns feed into it too, tipping the scale one way or another. Each tag forms when these markers cross fixed lines.

One part of the data matches another when it comes to risk groups, keeping how the system learns steady. A balance sits between types so nothing tips too far during training.

---

## Fine-Tuning Methodology

The base model is fine-tuned using:

* HuggingFace Transformers
* Parameter-Efficient Fine-Tuning (PEFT)
* LoRA (Low-Rank Adaptation)
* Instruction-response formatting

Training pipeline includes:

* Tokenization of instruction-response pairs
* Building prompts to get organized results
* Working through practice sessions using a steady pace plus fixed chunk sizes
* Evaluation at each epoch

Fewer resources are needed when using PEFT because it keeps results strong without demanding more space or effort.

---

## Performance Evaluation

Testing how the model acts involved these steps:

* Risk classification consistency
* Structured response formatting
* Financial reasoning quality
* Manual inspection of generated outputs

The fine-tuned model demonstrates:

* Improved financial domain awareness
* More consistent risk categorization
* Reduced generic responses
* Clear structured output formatting

---

## Running on Google Colab

A single click gets this notebook moving from start to finish. Little preparation needed. Running it straight through just works.

### Steps:

1. Open the notebook in Google Colab
2. Enable GPU runtime (Runtime → Change Runtime Type → GPU)
3. Get the needed tools ready - check the first cell for what’s inside. Start by setting up everything listed there
4. Run all cells sequentially

The notebook will:

* Generate the dataset
* Fine-tune the model
* Launch an interactive Gradio chatbot

No external configuration is required.

---

## Inference and Chatbot Demo

A small window opens once learning finishes, showing a chat interface built on Gradio tools.

**Example input:**

**Example output:**

The fine-tuned model provides:

* Structured responses
* Domain-specific reasoning
* Clear risk classification

Unlike the base model, it skips broad money talk that lacks clear risk analysis. Instead of vague summaries, you get sharper insights shaped by organized assessment steps. The earlier version just gives standard observations - no real depth in weighing dangers. Here, each point builds on a framework meant to spotlight threats clearly.

---

## Impact of Fine-Tuning

Before fine-tuning:

* Generic responses
* No structured risk level classification
* Inconsistent financial interpretation

After fine-tuning:

* Consistent risk labels
* Clear explanations
* Financial reasoning aligned with credit analysis standards

Fine-tuning small parts of a model helps it adjust better to new tasks. One way this works is by shifting how it handles different data types. Changes made locally can have broad impact across usage scenarios. The method shows promise without rewriting everything underneath.

---

## Technologies Used

* Python
* HuggingFace Transformers
* PEFT (LoRA)
* PyTorch
* Gradio
* Matplotlib

---

## Conclusion

From raw data collection to model deployment, FinLens AI shows what happens when large language models learn specific tasks in finance. Instead of general knowledge, it focuses on precise uses within financial systems. One step at a time, training moves through cleaning inputs, adjusting parameters, then testing outputs. Each phase connects tightly - no gaps, no loose ends. What emerges is not just theory but working technology shaped for real environments.

* Data generation
* Preprocessing
* Parameter-efficient fine-tuning
* Evaluation
* Interactive deployment

A real-world case shows how domain adaptation works when AI meets financial applications.
