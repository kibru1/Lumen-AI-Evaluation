# Lumen-AI-Evaluation
# Lumen AI Evaluation and Model Comparison

**TRP2 Lumen Challenge Submission**

## Author

- **Name:** Kibru Alemu
- **Email:** Kibrualemu812@gmail.com

## 1. Project Overview

This project evaluates AI-generated customer service responses for Lumen and investigates the performance of an alternative AI model.

The evaluation focuses on five criteria:

1. Accuracy
2. Human escalation
3. Complaint handling
4. Booking response quality
5. Channel consistency

## 2. Technologies Used

- Python
- Kaggle Notebooks
- Google Gemini API
- Google GenAI Python SDK (`google-genai`)
- JSON
- GitHub

## 3. Repository Structure

```text
Lumen-AI-Evaluation/
├── data/
│   ├── Lumen_Task4_Gemini4Neon_Prompts.json
│   └── Lumen_Task4_Responses.json
├── notebooks/
├── results/
├── README.md
├── requirements.txt
└── .gitignore
```

## 4. Evaluation Results – Task 3

The original assistant was evaluated using 20 examples.

| Criterion | Score |
|---|---:|
| Accuracy | 70% |
| Human escalation | 85% |
| Complaint handling | 90% |
| Booking response quality | 100% |
| Channel consistency | 90% |
| All five criteria passed | 40% |

## 5. Alternative Model Experiment – Task 4

- **Model:** Google Gemini 4 Hydrogen
- **Model ID:** `gemini-4-hydrogen`
- **Environment:** Kaggle Notebook

### Current progress

- E01: Successfully generated and saved.
- E02: HTTP 503 server error, including an unsuccessful retry.
- E03–E20: Not yet completed.
- Full evaluation scores: Pending.
- Model comparison: Pending.

Task 4 remains in progress. Missing responses and scores have not been fabricated.

## 6. Installation

Install the required packages:

```bash
pip install -r requirements.txt
```

## 7. API Configuration

Configure your Gemini API key in Kaggle Secrets using:

`GEMINI_API_KEY`

Never upload API keys or passwords to GitHub.

## 8. Project Status

| Task | Status |
|---|---|
| Task 1 – Business priorities | Completed |
| Task 2 – Conversation analysis | Completed |
| Task 3 – Original response evaluation | Completed |
| Task 4 – Alternative model experiment | In progress |
| Task 5 – Fix specification | Completed |
| Task 6 – Email to Dana | Completed |
| Task 7 – Reflection | Completed |

## 9. Next Steps

1. Complete the remaining 19 Gemini 4 Hydrogen test cases.
2. Evaluate all 20 responses.
3. Calculate scores for all five criteria.
4. Compare the alternative model with the original assistant.
5. Update the final report.

## 10. Conclusion

This project establishes a baseline evaluation of Lumen's AI customer service responses and documents an ongoing experiment with Google Gemini 4 Hydrogen.

The original evaluation is complete. The alternative-model experiment requires further execution and scoring before a complete comparison can be reported.
