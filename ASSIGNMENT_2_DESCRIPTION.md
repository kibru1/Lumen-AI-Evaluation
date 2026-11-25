# Lumen AI Evaluation and Model Comparison
## TRP2 Lumen Challenge Submission Report

**Project:** Lumen AI Evaluation and Model Comparison  
**Alternative AI model selected:** Google Gemini 4 Hydrogen  
**Model ID:** `gemini-4-hydrogen`  
**Date:** 25 November 2026

---

## 1. Introduction

This project evaluates the quality of AI-generated customer service responses for the Lumen business. The evaluation focuses on whether responses are accurate, handle customer complaints appropriately, identify situations requiring human assistance, provide suitable booking information, and maintain consistency across communication channels.

The project also includes an evaluation of an alternative AI model using the same customer examples and evaluation criteria applied in the original assessment.

## 2. Evaluation Criteria

Five criteria are used to assess response quality:

1. **Accuracy:** Does the response provide correct information?
2. **Human escalation:** Does it recognize situations that require staff assistance?
3. **Complaint handling:** Does it respond appropriately to customer complaints?
4. **Booking response quality:** Does it provide clear and useful booking information?
5. **Channel consistency:** Does it maintain consistent information across communication channels?

## 3. Task Completion Summary

| Task | Description | Status |
|---|---|---|
| Task 1 | Business priorities | Completed |
| Task 2 | Conversation analysis | Completed |
| Task 3 | Evaluation of original responses | Completed |
| Task 4 | Alternative AI model experiment | In progress |
| Task 5 | Fix specification | Completed |
| Task 6 | Email to Dana | Completed |
| Task 7 | Reflection | Completed |

## 4. Task 3: Verified Evaluation Results

The original 20 examples were reviewed and scored using the five evaluation criteria.

| Evaluation criterion | Passed | Score |
|---|---:|---:|
| Accuracy | 14/20 | 70% |
| Human escalation | 17/20 | 85% |
| Complaint handling | 18/20 | 90% |
| Booking response quality | 20/20 | 100% |
| Channel consistency | 18/20 | 90% |
| All five criteria passed | 8/20 | 40% |

### Interpretation

Booking response quality achieved the highest result at 100%. Accuracy was the weakest individual criterion at 70%, indicating that factual correctness deserves particular attention. Although most responses passed the individual criteria, only 40% passed all five criteria simultaneously. This shows the importance of evaluating responses across multiple dimensions rather than relying on one overall impression.

## 5. Task 4: Alternative AI Model Experiment

### 5.1 Model selection

Google Gemini 4 Hydrogen was selected as the alternative model for the experiment.

- Model: Google Gemini 4 Hydrogen
- Model identifier: `gemini-4-hydrogen`
- API package: `google-genai`
- Environment: Kaggle Notebook
- Input dataset: `Lumen_Task4_Gemini4Neon_Prompts.json`
- Output file: `Lumen_Task4_Responses.json`

The experiment was designed to use the same 20 evaluation examples, the same Lumen business information, and the same five evaluation criteria.

### 5.2 Experiment progress

The first example, E01, was successfully generated and saved.

**E01 generated response:**

> Hi! At Lumen Austin South Congress, the Unlimited membership is $149 per month. If you're a first-time visitor (18+), you can also start with a free trial class, and new members can get an Intro Month for $99 if purchased within 7 days of their trial. Let me know if you'd like to book a free trial!

The next example, E02, encountered a server error (HTTP 503) indicating that the model was experiencing high demand. A retry was also unsuccessful.

**Current experiment status:**

- Successfully generated responses: 1 of 20
- Remaining responses: 19
- Evaluation scores for all 20 responses: Not yet available
- Comparison with the original model: Pending

### 5.3 Limitations

The alternative-model experiment is not complete. Because only one response was successfully generated, it would not be methodologically appropriate to calculate final scores for all 20 examples or claim a complete comparison.

The remaining examples must be generated and evaluated before Task 4 can be considered complete.

## 6. Task 5: Fix Specification

The project includes a fix specification addressing the response-quality issues identified during the evaluation. The improvements should prioritize factual accuracy, appropriate escalation to human staff, effective complaint handling, clear booking information, and consistent responses across channels.

## 7. Task 6: Email to Dana

The email task was completed as part of the assignment. It communicates the relevant project findings and recommendations.

## 8. Task 7: Reflection

The evaluation demonstrates that AI customer-service quality requires more than producing fluent and friendly responses. Responses must also be factually correct, consistent, and capable of recognizing when a human employee should become involved.

The original evaluation showed strong booking response quality, but accuracy and overall performance across all five criteria remain areas for improvement.

The alternative-model experiment also highlighted a practical challenge: API availability and server errors can interrupt evaluation work. A reliable experiment therefore requires saved outputs, controlled retries, and clear documentation of incomplete cases.

## 9. Conclusion

The project completed the business-priority analysis, conversation analysis, original response evaluation, fix specification, email task, and reflection. The original evaluation identified both strengths and areas requiring improvement in Lumen's customer-service responses.

The alternative AI model experiment was started using Google Gemini 4 Hydrogen. However, only one of the 20 required responses was successfully generated. The remaining responses and their evaluations are still required before a valid model comparison can be reported.

**Final submission status: Tasks 1, 2, 3, 5, 6, and 7 are completed. Task 4 remains in progress and must be completed before the assignment can be described as fully finished.
