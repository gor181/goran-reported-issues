---
  title: "Test"
  description: "Test"
  v2: true

---
## Sample exercise

```yaml
type: NormalExercise
lang: python
xp: 100
skills: 2
key: a67e16a125



```

In the Python script on the right, you can type Python code to solve the exercises. If you hit _Run Code_ or _Submit Answer_, your python script (`script.py`) is executed and the output is shown in the IPython Shell. _Submit Answer_ checks whether your submission is correct and gives you feedback.

You can hit _Run Code_ and _Submit Answer_ as often as you want. If you're stuck, you can click _Get Hint_, and ultimately _Get Solution_.

You can also use the IPython Shell interactively by simply typing commands and hitting Enter. When you work in the shell directly, your code will not be checked for correctness so it is a great way to experiment.

`@instructions`
- Experiment in the IPython Shell; type `5 / 8`, for example.
- Add another line of code to the Python script: `print(7 + 10)`.
- Hit _Submit Answer_ to execute the Python script and receive feedback.

`@hint`
Simply add `print(7 + 10)` in the script on the right and hit 'Submit Answer'.

`@pre_exercise_code`
```{python}
# pec comes here
```
`@sample_code`
```{python}
# Example, do not modify!
print(5 / 8)

# Put code below here

```
`@solution`
```{python}
# Example, do not modify!
print(5 / 8)

# Put code below here
print(7 + 10)
```
`@sct`
```{python}
msg = "Don't remove the first statement. It is an example which is coded for you!"
test_function("print", 1, not_called_msg = msg, incorrect_msg = msg)

msg = "Have you added `print(7 + 10)` to the script, in addition to the `print()` command that was already there?"
test_function("print", 2, not_called_msg = msg, incorrect_msg = msg)
success_msg("Great!")
```




