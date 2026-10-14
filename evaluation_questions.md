# AI Evaluation: Electrical Engineering Questions

## Question 1: Python Code Correctness

### Prompt
Write a Python function that calculates the arithmetic mean of a list of numbers. The function should return an appropriate result when the list is empty.

### Reference Answer
```python
def calculate_mean(numbers):
    if not numbers:
        return None
    return sum(numbers) / len(numbers)
```

### Evaluation Criteria
1. The function calculates the arithmetic mean correctly.
2. It handles an empty list without raising a division-by-zero error.
3. The code is syntactically valid.
4. The implementation is clear and concise.

### Common Errors to Detect
- Dividing by zero for an empty list.
- Using an incorrect denominator.
- Returning an incorrect result for valid numeric input.

### Scoring
- 4: All criteria satisfied.
- 3: Correct calculation with a minor issue.
- 2: Partially correct implementation.
- 1: Major logical or implementation errors.
- 0: Invalid or irrelevant answer.

## Question 2: Electrical Engineering Reasoning

### Prompt
Why can a high-resistance single-line-to-ground fault be more difficult for a conventional distance relay to detect than a low-resistance fault?

### Reference Answer
A high-resistance fault can increase the apparent impedance measured by the distance relay. The measured impedance may fall outside the relay's configured operating characteristic, potentially preventing the relay from starting or operating as intended. The actual response depends on the network configuration, relay settings, fault location, and measurement conditions.

### Evaluation Criteria
1. Explains the effect of fault resistance on apparent impedance.
2. Connects the impedance change to the relay's operating characteristic.
3. Avoids claiming that every high-resistance fault will be missed.
4. Recognizes that network conditions and relay settings affect the result.

### Scoring
- 4: Technically correct, complete, and appropriately qualified.
- 3: Correct core explanation with a minor omission.
- 2: Partially correct explanation.
- 1: Major technical misunderstanding.
- 0: Incorrect or irrelevant answer.

## Evaluation Principle
AI-generated answers should be judged against the reference answer and explicit criteria, rather than fluency or confidence alone.
