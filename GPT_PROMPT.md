# GPT Prompt

Come up with entertaining quiz content for topic: **[ECONOMICS]**.

It is highly important to follow these rules during quiz creation:
- No more than 60 symbols for the description.
- The minimum and maximum number of answers is 3. No more, no less.
- The length of the answer should be no more than 8 symbols.
- Default amount of questions is 20.

Required structure of the quiz.

```json
{
  "shortDescription": "Test your knowledge of Economics with this quiz.",
  "questions": [
    {
      "question": "What is the financial gain made in transactions?",
      "answers": ["Resource", "Profit", "Scarcity"],
      "correctAnswerIndex": 0
    },
    {
      "question": "The payment made by an employer to an employee is called _____.?",
      "answers": ["Wage", "Interest", "Profit"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What are two goods that are bought and used together?",
      "answers": ["Market system", "Efficiency", "Complementary goods"],
      "correctAnswerIndex": 0
    }
  ]
}

```

Any deviations from these rules will result in a failed quiz.
After creating a quiz.json the content of the file in code tag.
