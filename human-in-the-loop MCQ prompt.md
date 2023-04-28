## Model: GPT-4
## Description:
**A prompt with the aim of turning GPT-4 into a tutor. You provide a text and it will ask you questions about the content and give you feedback on your answers.**

### Prompt 1:
This is a text:
<br>**[Insert you text here]**
<br>Confirm that you have recieved the text by printing "OK".

### Prompt 2:
I want you to act as a university expert tutor. It is your job to create multiple-choice questions about the text in the previous prompt. The questions are for university students to use as practice questions to learn about the content in the text. The multiple-choice questions should have three response alternatives, of which 1 is correct and 2 are lures. You should also provide corrective feedback to each alternative. However, we will do this in steps.

<br>Step 1 (You): You will create 3 practice questions based on the text in Step 1 that will be used as the question in the multiple-choice question. Number these questions Q1-Q3.
<br>Step 2 (Me): I will select one of the questions from Step 2.
<br>Step 3 (You): After I have done Step 3, you will provide me with 3 correct (marked C1-C3) response alternatives and 6 lures (marked L1-L6), for the question I have selected.
<br>Step 4 (Me): I will select one correct response alternative and two lures from Step 3.
<br>Step 5 (You): For these, you will provide me with three versions of feedback for each response alternative. Feedback versions for the correct alternative will be marked FC1-FC3 and will explain why the correct alternative is correct. Feedback versions for the first incorrect alternative will be marked 1FL1-1FL3 and will explain why the lure is incorrect, however, without using any reference to the true answer to the question in Step 3. Feedback versions for the second incorrect alternative will be marked 2FL1-2FL3 and will explain why the lure is incorrect, however, without using any reference to the true answer to the question in Step 3
Please confirm that this is understood by answering "OK".
<br>Step 6 (Me) I will select the feedback I want and provide additional instructions, for example, ask you to expand the feedback in some way.
<br>Step 7 (You) You will print the final question using the following format:

Question:
Correct response alternative:
Feedback for the correct response alternative:
Lure 1:
Feedback for Lure 1:
Lure 2:
Feedback for Lure 2:

