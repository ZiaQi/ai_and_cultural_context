# LLM Performance Analysis on Chinese Social Work Professional Standards

This study evaluates the performance of Large Language Models (LLMs) on the Chinese Social Work Licensing Examination through a combination of quantitative and qualitative analyses. <br/>
arXiv:

## 1. Model Testing
The notebook tests LLMs on both jurisprudence and applied knowledge sections of the Chinese Social Work Licensing Examination
- Chinese Models: Qwen, ERNIE, DeepSeek, Kimi
- Western Models: GPT-4, Claude, Mistral, Gemini

## 2. Quantitative Analysis
- Score calculation for different question types
- Performance comparison across models
- Regional performance comparison (Chinese vs Western models)

## 3. Qualitative Analysis
- Random sampling of model responses
- Labeling results processing
- Detailed analysis capabilities

## 4. User Prompts
Handles both single-choice and multiple-choice questions.
- Condition 1: Explicit instructions with mandatory answers
- Condition 2: Optional question skipping
- Condition 3: Answer options only (no question stems)

## 4. Data Structure
**Input Data**
- Exam questions in CSV format
- Prompt templates in TXT format <br/>

**Output Data**
- Test results in CSV format
- Analysis results in CSV format

