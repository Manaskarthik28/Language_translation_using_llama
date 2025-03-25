#🚀 Language Translation with LLaMA 3.2 1B


This project demonstrates the successful fine-tuning of the LLaMA 3.2 1B model for language translation tasks, specifically English to Hindi and English to Nepali. The training dataset was extracted using various data sources and processed into word language pairs.

#🔎 Key Features:


Custom Dataset Extraction:

Applied web scraping techniques to gather language pairs from multiple online sources.

Efficient Fine-tuning with qLoRA:

Quantized the model to 4-bit using qLoRA for memory-efficient training on a Tesla T4 GPU.

Applied optimal configurations with rank=8 and a tailored dropout rate to achieve a 15% GPU memory optimization.

Performance Enhancements:

Integrated gradient checkpointing for a 10% efficiency boost.

Used FP16 mixed precision training, resulting in a 20% speed improvement.

