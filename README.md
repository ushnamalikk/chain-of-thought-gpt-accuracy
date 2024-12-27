# GPT o1-Preview Integrated CoT Reasoning

This repository aims to explore how integrated chain-of-thought reasoning in GPT o1-preview affects response accuracy compared to GPT-3.5, across trivia questions of varying formats, categories, and difficulty levels. Below is a description of the included files:

## Files

### 1. `boolean_gpt_3.5_results.json`
- **Description**: Contains GPT-3.5's responses to True/False questions sourced from the trivia dataset.
- **Purpose**: To evaluate GPT-3.5's accuracy in answering simple True/False trivia questions.

### 2. `boolean_gpt_o1_results.json`
- **Description**: Contains GPT o1-preview's responses to True/False questions sourced from the trivia dataset.
- **Purpose**: To evaluate the impact of integrated chain-of-thought reasoning in GPT o1-preview for answering True/False trivia questions.

### 3. `mcq_gpt_o1_results.json`
- **Description**: Contains GPT o1-preview's responses to multiple-choice (MCQ) questions from the trivia dataset.
- **Purpose**: To assess GPT o1-preview's performance in answering multiple-choice trivia questions using integrated chain-of-thought reasoning.

### 4. `multiple_gpt_3.5_results.json`
- **Description**: Contains GPT-3.5's responses to multiple-choice (MCQ) questions from the trivia dataset.
- **Purpose**: To evaluate GPT-3.5's accuracy in multiple-choice trivia scenarios.

### 5. `cleaned_trivia_data.csv`
- **Description**: The complete trivia dataset used in this analysis. It includes:
  - **Question types**: True/False and Multiple-Choice (MCQ)
  - **Categories**: Various trivia topics
  - **Difficulty levels**: Spanning from easy to hard
  - **Number of entries**: Approximately 4,000
- **Purpose**: Serves as the dataset for evaluating GPT models on diverse trivia questions.

