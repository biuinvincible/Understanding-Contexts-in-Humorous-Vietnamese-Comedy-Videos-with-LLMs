# Understanding Contexts in Humorous Vietnamese Comedy Videos with LLMs

## Introduction
Humor is a complex and culturally dependent concept that plays a significant role in Vietnamese entertainment culture. This project aims to explore the elements that contribute to humor in Vietnamese comedy videos by constructing a comprehensive dataset and analyzing linguistic, acoustic, and visual features.

We leverage state-of-the-art Large Language Models (LLMs) and multimodal data processing techniques to understand how language, speech intonation, and situational context interact to create humor. The project's insights pave the way for better computational humor analysis and practical applications in media content recognition.

## Objectives
- Build a comprehensive dataset of Vietnamese comedy videos.
- Extract multimodal features, including textual, acoustic, and visual elements.
- Use LLMs to analyze and generate explanations for humor contexts.
- Evaluate and compare the performance of different LLMs.

## Dataset
The dataset consists of nearly **200 video samples** curated from Vietnamese entertainment platforms such as YouTube and TikTok. The videos vary in duration from **2 seconds to over 1 minute**, providing diverse contexts for humor analysis.

### Features Extracted:
1. **Textual (Utterances):** Transcriptions of dialogues.
2. **Acoustic Features:** Pitch, intensity, tempo, and other audio characteristics.
3. **Visual Descriptions:** Scene settings, facial expressions, and other visual elements.

The extracted dataset is ready for model training and evaluation, providing a rich resource for humor context understanding.

## Methodology
### Model Implementation
- Employed **Meta-Llama-3.1-405B**, **Llama-3.3-70B**, and **Mixtral-8x22B** models.
- Automated prompt creation using Python scripts for both **zero-shot** and **few-shot learning** approaches.

## Results
The evaluation metrics used include ROUGE, BLEU, and BERTScore.

### Performance Highlights
- **Few-shot Learning:** Meta-Llama-3.1-405B achieved the highest scores with:
  - ROUGE-1: **0.7047**
  - ROUGE-2: **0.3778**
  - BLEU: **0.1292**
  - BERTScore: **0.7612**
- **Zero-shot Learning:** Meta-Llama-3.1-405B demonstrated the best results across most metrics, outperforming other models.

## Contributions
- **Data Collection:** Curated and annotated video samples for humor context.
- **Feature Extraction:** Processed multimodal features (text, audio, and visual).
- **Model Development:** Created and optimized prompt templates for LLM inference.
- **Evaluation:** Compared model performances and analyzed errors.

## Impact
This project opens new avenues for **processing Vietnamese video data** in the context of **video interpretation tasks**, contributing valuable insights into computational humor analysis.

## Conclusion
Our findings demonstrate that LLMs can effectively generate context-aware explanations for humor in Vietnamese comedy videos. Meta-Llama-3.1-405B proved to be the most robust model for this task, although further improvements through fine-tuning may enhance its understanding of cultural nuances.

## Repository Structure
- `data/`: Contains the pre-extracted dataset samples.
- `scripts/`: Python scripts for model evaluation.
- `results/`: Evaluation metrics and performance reports.

## Future Directions
- Expand the dataset to include more diverse samples.
- Fine-tune LLMs for better understanding of cultural humor.
- Develop real-time video interpretation systems.

## Authors
- Ta Anh Khoa
- Nguyen Huy Hoang
- Chau Nguyen Tri Vu

## Contact
For more information, please contact https://github.com/biuinvincible.
