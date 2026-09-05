# Assignment 2 – GPT-2 Text Generation Parameter Experiments

## 📌 Overview

This assignment explores **Generative AI text generation using the GPT-2 language model**. The main objective is to understand how different text-generation parameters affect the output produced by GPT-2.

The experiments were implemented using **Python and Google Colab** with the Hugging Face Transformers library.

## 🎯 Objectives

* Load and use the GPT-2 language model.
* Generate text using a predefined prompt.
* Experiment with different text-generation parameters.
* Compare the effect of Temperature, Top-K, Top-P, and Repetition Penalty.
* Generate multiple versions of a custom prompt.
* Observe how different parameter values influence generated text.

## 🛠️ Tools & Technologies

* Python
* Google Colab
* PyTorch
* Hugging Face Transformers
* GPT-2

## 🤖 Model Used

**GPT-2**

Model: `openai-community/gpt2`

The GPT-2 tokenizer and language model are loaded using the Hugging Face Transformers library.

## 📝 Original Prompt

The main prompt used for the experiments was:

> **"The future of artificial intelligence will"**

The model generated different continuations of this prompt by changing individual generation parameters.

## 🧪 Experiments

### Experiment 1 – Temperature

**Temperature: 0.3**

A lower temperature was used to observe more focused and less varied text generation.

### Experiment 2 – Temperature

**Temperature: 1.5**

A higher temperature was used to observe more varied and creative text generation.

### Experiment 3 – Top-K

**Top-K: 20**

Top-K sampling was used to restrict token selection to the top 20 probable tokens.

### Experiment 4 – Top-P

**Top-P: 0.7**

Top-P sampling was used to control token selection based on cumulative probability.

### Experiment 5 – Repetition Penalty

**Repetition Penalty: 1.5**

A repetition penalty was applied to reduce repeated words and phrases in the generated text.

## ⚙️ Generation Settings

The text generation function uses the following parameters:

| Parameter            | Purpose                                               |
| -------------------- | ----------------------------------------------------- |
| `temperature`        | Controls randomness in generated text                 |
| `top_k`              | Limits token selection to the top K candidates        |
| `top_p`              | Controls token selection using cumulative probability |
| `repetition_penalty` | Helps reduce repeated text                            |
| `max_new_tokens`     | Controls the maximum number of newly generated tokens |

The notebook uses **80 maximum new tokens** for generation.

## ✍️ Custom Prompt Experiment

A custom story prompt was also tested:

> **"When Maya opened the old wooden box, she discovered a small device that could predict events twenty-four hours before they happened."**

Three different versions were generated using different combinations of Temperature, Top-K, Top-P, and Repetition Penalty.

### Custom Version 1

* Temperature: **0.5**
* Top-K: **30**
* Top-P: **0.9**
* Repetition Penalty: **1.1**

### Custom Version 2

* Temperature: **0.9**
* Top-K: **50**
* Top-P: **0.95**
* Repetition Penalty: **1.1**

### Custom Version 3

* Temperature: **1.2**
* Top-K: **50**
* Top-P: **0.95**
* Repetition Penalty: **1.2**

## 🔥 High Temperature Experiment

An additional experiment was performed using:

**Temperature: 2.0**

This experiment was used to observe the effect of a very high temperature on GPT-2's generated output.

## 📊 Results

The experiments produced different text outputs depending on the generation parameters.

The assignment demonstrates that changing parameters such as **temperature, Top-K, Top-P, and repetition penalty** can significantly influence the style, randomness, diversity, and repetition of generated text.

## 📂 Files Included

```text
Assignment-2/
│
├── Gen_Ai_assigment_2.ipynb
└── README.md
```

## 🎓 Learning Outcomes

After completing this assignment, I learned:

* How to load and use GPT-2 for text generation.
* How text-generation parameters influence AI-generated content.
* How Temperature affects randomness.
* How Top-K controls the number of candidate tokens.
* How Top-P controls token selection based on cumulative probability.
* How Repetition Penalty can reduce repetitive outputs.
* How to compare different generated outputs.
* How to perform Generative AI experiments using Python and Google Colab.

## ✅ Conclusion

This assignment provided practical experience with **GPT-2 and Generative AI text generation**. By changing Temperature, Top-K, Top-P, and Repetition Penalty, different characteristics of the generated text could be observed. The custom prompt and high-temperature experiments further demonstrated how generation settings can affect the final output.

## 👨‍💻 Author

**[Your Name]**

Generative AI / Artificial Intelligence Student
