# Prompts for `confest.py`

Use the prompt that matches the task. Apply it to [`confest.py`](./confest.py) and any directly related files.

## Bug fixes

> Find and fix the bug in `confest.py` described here: **[describe the observed problem]**.
>
> Trace the cause before editing. Make the smallest complete fix, preserve the script’s intended behavior (search Google for `Python Selenium` and print the page title), and handle errors clearly. Do not hide failures or make unrelated changes. Run the relevant checks and summarize the cause, fix, and validation.

## Code correction

> Correct `confest.py` for the issue or requirement below: **[describe what is incorrect or what should happen]**.
>
> Check the existing code and relevant context first. Make the behavior match the requirement, preserve unrelated behavior, and follow the project’s Python style. Avoid unnecessary rewrites. Run relevant checks and summarize what changed.

## Code improvement suggestions

> Review `confest.py` and suggest practical improvements to its correctness, reliability, readability, and maintainability.
>
> Do not edit files. For each suggestion, explain the benefit and point to the relevant code. Prioritize issues that matter; distinguish necessary fixes from optional improvements.

## Implement code improvements

> Improve `confest.py` for correctness, reliability, readability, and maintainability.
>
> Preserve its purpose: search Google for `Python Selenium` and print the page title. Keep the browser lifecycle safe so the driver is closed even when an error occurs, use explicit waits instead of fixed sleeps, and handle Google’s automated-traffic challenge clearly rather than treating it as successful results. Make only relevant changes, run the available checks, and summarize the changes and results.
