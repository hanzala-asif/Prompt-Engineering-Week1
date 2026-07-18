# Results Comparison

| AI Tool | Zero-Shot Accuracy | Few-Shot Accuracy |
|----------|-------------------|-------------------|
| ChatGPT | 10/10 | 10/10 |
| Gemini | 9/10 | 9/10 |
| Claude | 9/10 | 9/10 |


<img width="275" height="417" alt="Screenshot 2026-07-16 061625" src="https://github.com/user-attachments/assets/06ac91b7-cbfc-4b65-996c-82fd8531d39e" />
<img width="229" height="289" alt="Screenshot 2026-07-16 061615" src="https://github.com/user-attachments/assets/17790cf4-94e3-4509-ac53-29604a3c41c0" />
<img width="257" height="358" alt="Screenshot 2026-07-16 061535" src="https://github.com/user-attachments/assets/4c65d3af-b6c5-4acb-8eef-6f984b4b5bda" />
<img width="186" height="307" alt="Screenshot 2026-07-16 061405" src="https://github.com/user-attachments/assets/e10587bb-088d-44b3-8921-c2617c7a10d6" />



## Observation

ChatGPT correctly classified all ten messages.

Gemini and Claude classified Message 10 ("Why was I charged twice for my purchase?") as a Complaint instead of a Question.

The message contains both a question and an expression of dissatisfaction, making it somewhat ambiguous.

## Conclusion

Few-shot prompting generally provides better guidance to AI models by showing examples of the expected output. However, because this dataset contained simple and straightforward customer support messages, there was no noticeable improvement in accuracy between zero-shot and few-shot prompting. On more complex tasks, few-shot prompting is likely to produce more consistent and reliable results.
