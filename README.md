# DigitPredictor

DigitPredictor is a simple number guessing game implemented in Python. The game challenges players to guess a randomly generated number within a specified range in a limited number of attempts.

## Features

- User-defined range for the random number
- Dynamic calculation of allowed guesses based on the range
- Feedback on each guess (higher/lower)
- Game over when the number is guessed or attempts are exhausted

## How to Play

1. Run the script
2. Enter the minimum and maximum numbers for the range
3. The game will calculate the number of attempts allowed
4. Start guessing!
5. After each guess, you'll be told if the actual number is higher or lower
6. Keep guessing until you find the number or run out of attempts

## Technical Details

- The game uses Python's `random` module to generate a random number
- The number of allowed attempts is calculated using the logarithm base 2 of the range size, ensuring a fair challenge regardless of the range
- Input validation is implemented to ensure the minimum number is less than the maximum number

## Requirements

- Python 3.x

## How to Run

```
python digit_predictor.py
```

