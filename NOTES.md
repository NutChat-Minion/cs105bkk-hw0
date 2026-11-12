# HW0 notes

Answer each question in a few sentences. Be specific: name the function, the error or the command.

## What did you try?
I created a virtual environment and installed pytest to run the provided tests. I implemented add_item() using dictionary copying, total_items() using *inventories, and running_low() using list comprehension and sorting.
## What broke, and how did you fix it?
Initially, I couldn't activate my virtual environment because I was using fish shell, which requires activate.fish instead of the regular activation script. I also created the virtual environment outside the homework repository. I fixed this by navigating into cs105bkk-hw0, creating a new .venv, and activating it with source .venv/bin/activate.fish.
## What would you do differently next time?
I would check my current working directory and shell type before creating a virtual environment. I would also verify that Python and pip are working before installing packages or running tests.