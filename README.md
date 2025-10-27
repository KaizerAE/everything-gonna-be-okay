# everything-gonna-be-okay

A simple Python script to remind you that everything's gonna be okay. Sometimes we all need a little reassurance.

## Python Code

```python
# A simple script to remind you that everything's gonna be okay
import time

def everything_is_okay():
    """Display a reassuring message repeatedly"""
    while True:
        print("Everything's gonna be okay")
        time.sleep(1)

if __name__ == "__main__":
    try:
        everything_is_okay()
    except KeyboardInterrupt:
        print("\nRemember: Everything's gonna be okay!")
```

## How to Run

1. Save the code to a file (e.g., `everything_okay.py`)
2. Run it with: `python everything_okay.py`
3. Press `Ctrl+C` to stop

## Description

This script continuously displays the message "Everything's gonna be okay" every second. It's a simple reminder during tough times that things will get better. 💙
