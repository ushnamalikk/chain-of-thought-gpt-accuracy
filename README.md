# GPT o1-Preview CoT Reasoning

This repository contains files and results related to evaluating the response accuracy of GPT models (GPT-3.5 and GPT-01-Preview) on trivia datasets, with a focus on integrated chain-of-thought (CoT) reasoning. Below is a description of the included files:

## Files

### 1. `boolean_gpt_3.5_results.json`
- **Description**: Contains GPT-3.5's responses to True/False questions sourced from the trivia dataset.
- **Purpose**: To evaluate GPT-3.5's accuracy in answering simple True/False trivia questions.

### 2. `boolean_gpt_o1_results.json`
- **Description**: Contains GPT-01-Preview's responses to True/False questions sourced from the trivia dataset.
- **Purpose**: To evaluate the impact of integrated chain-of-thought reasoning in GPT-01-Preview for answering True/False trivia questions.

### 3. `mcq_gpt_o1_results.json`
- **Description**: Contains GPT-01-Preview's responses to multiple-choice (MCQ) questions from the trivia dataset.
- **Purpose**: To assess GPT-01-Preview's performance in answering multiple-choice trivia questions using integrated chain-of-thought reasoning.

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

---

## Purpose of the Repository
This repository aims to explore how integrated chain-of-thought reasoning in GPT-01-Preview affects response accuracy compared to GPT-3.5, across trivia questions of varying formats, categories, and difficulty levels.

---

## Usage
- **Data Files**: Use the `.json` files to analyze the models' responses for specific question types (True/False or MCQs).
- **Dataset**: Refer to `cleaned_trivia_data.csv` for the original dataset and create your own tests or validations.

---

## Contact
For any questions or clarifications, feel free to reach out via the repository's issue tracker.
