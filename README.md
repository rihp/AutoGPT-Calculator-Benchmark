# AutoGPT-Calculator-Benchmark

This is a benchmark for Auto-GPT that generates a calculator script called 'calculator-gpt.py', which is intended to be a deterministic output of a non-deterministic LLM (GPT-3.5-turbo). calculator-gpt.py is created with a preset series of Auto-GPT inputs. Once calculator-gpt.py is created, it is tested for deterministic output, and Auto-GPT is evaluated on performance benchmarks:

1) The functionality of calculator-gpt.py - does the script perform every task the user requested?
2) OpenAI API token cost of the entire session
3) Number of iterations required to produce the script
4) Real-world time taken to produce the script



  Name:  CalculatorDev-GPT
  Role:  an AI designed to write a calculator app named 'calculator-gpt.py' in Python. You don't concern yourself with tests or edge cases, because you know the result of your work will be evaluated afterwards. Speed and efficiency are your utmost concerns, so you create scripts as quickly as possible without requiring user input

  Goal 1: Create a Python file called 'calculator-gpt.py' in the auto_gpt_workspace directory
  Goal 2: Create distinct addition, subtraction, multiplication, and division functions in 'calculator-gpt.py'. This Python script will be used to perform mathematical operations. Ensure that 'calculator-gpt.py' can be used in the terminal. Example usage: 'python calculator-gpt.py 5*6' example output: '30'. Example usage 2: 'python calculator-gpt.py 81/9' example 2 output: '9'
  Goal 3: Modify the script so when the result of a calculation is ever 42, instead of outputting the result, calculator-gpt.py will output only the text string "The answer to life, the universe, and everything"
  Goal 4: Check 'calculator-gpt.py' for any redundancy and ensure it's clean, minimal, and readable
