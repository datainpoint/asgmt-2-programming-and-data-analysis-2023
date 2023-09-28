# asgmt-2-programming-and-data-analysis-2023

> Assignment 2: Programming and Data Analysis 2023.

Define functions in `asgmt-two.py` with given names and templates then run `test-runner.py`.

## 01. Define a function `are_all_vowels_contained()` which returns whether input text contains all the vowels: a, e, i, o, u.

```python
def are_all_vowels_contained(x: str) -> bool:
    """
    >>> are_all_vowels_contained('python')
    False
    >>> are_all_vowels_contained('anaconda')
    False
    >>> are_all_vowels_contained('reticulate')
    False
    >>> are_all_vowels_contained('anaconda and reticulate')
    True
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 02. Define a function `convert_bools_to_yes_no()` which returns boolean `False` as `'No'` and boolean `True` as `'Yes'`.

```python
def convert_bools_to_yes_no(x: bool) -> str:
    """
    >>> convert_bools_to_yes_no(False)
    'No'
    >>> convert_bools_to_yes_no(True)
    'Yes'
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 03. Define a function `convert_bools_to_heads_or_tails()` which returns boolean `False` as `'Tails'` and boolean `True` as `'Heads'`.

```python
def convert_bools_to_heads_or_tails(x: bool) -> str:
    """
    >>> convert_bools_to_heads_or_tails(False)
    'Tails'
    >>> convert_bools_to_heads_or_tails(True)
    'Heads'
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 04. Define a function `convert_integers_to_weekdays()` which converts integers to weekday names, as described in docstring.

```python
def convert_integers_to_weekdays(x: int) -> str:
    """
    >>> convert_integers_to_weekdays(0)
    'Sunday'
    >>> convert_integers_to_weekdays(1)
    'Monday'
    >>> convert_integers_to_weekdays(2)
    'Tuesday'
    >>> convert_integers_to_weekdays(3)
    'Wednesday'
    >>> convert_integers_to_weekdays(4)
    'Thursday'
    >>> convert_integers_to_weekdays(5)
    'Friday'
    >>> convert_integers_to_weekdays(6)
    'Saturday'
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 05. Define a function `convert_month_names_to_integers()` which converts month names to integers, as described in docstring.

```python
def convert_month_names_to_integers(x: str) -> int:
    """
    >>> convert_month_names_to_integers('January')
    1
    >>> convert_month_names_to_integers('February')
    2
    >>> convert_month_names_to_integers('November')
    11
    >>> convert_month_names_to_integers('December')
    12
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 06. Define a function `describe_bmi()` which returns the description of BMI with 3 levels: `"Underweight"`, `"Normal weight"`, or `"Overweight"` given a person's height in centimeters and weight in kilograms.

$$
\text{BMI} = \frac{\text{Weight}_{\text{kg}}}{\text{Height}_{\text{m}}^2}
$$

|BMI|Description|
|:---:|-----------|
|$< 18.5$|Underweight|
|$18.5 – 24.9$|Normal weight|
|$25.0 - $|Overweight|

```python
def describe_bmi(height: int, weight: int) -> str:
    """
    >>> describe_bmi(172, 50)
    'Underweight'
    >>> describe_bmi(172, 65)
    'Normal weight'
    >>> describe_bmi(175, 100)
    'Overweight'
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 07. Define a function `is_upper_or_lower_cased()` which returns `"Upper-cased"` if intput alphabet is upper-cased, otherwise returns `"Lower-cased"`.

```python
def is_upper_or_lower_cased(x: str) -> str:
    """
    >>> is_upper_or_lower_cased("a")
    'Lower-cased'
    >>> is_upper_or_lower_cased("A")
    'Upper-cased'
    >>> is_upper_or_lower_cased("z")
    'Lower-cased'
    >>> is_upper_or_lower_cased("Z")
    'Upper-cased'
    >>> is_upper_or_lower_cased("e")
    'Lower-cased'
    >>> is_upper_or_lower_cased("E")
    'Upper-cased'
    >>> is_upper_or_lower_cased("b")
    'Lower-cased'
    >>> is_upper_or_lower_cased("B")
    'Upper-cased'
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 08. Define a function `reverse_vowel()` which swaps a vowel's case and does nothing given a non-vowel alphabet.

```python
def reverse_vowel(x: str) -> str:
    """
    >>> reverse_vowel("a")
    'A'
    >>> reverse_vowel("A")
    'a'
    >>> reverse_vowel("z")
    'z'
    >>> reverse_vowel("Z")
    'Z'
    >>> reverse_vowel("e")
    'E'
    >>> reverse_vowel("E")
    'e'
    >>> reverse_vowel("b")
    'b'
    >>> reverse_vowel("B")
    'B'
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 09. Define a function `categorize_nikes_running_shoes()` which returns Nike's running shoe series given its features.

|Series|Has ZoomX|Has Carbon Plate|Has Airbag|
|------|---------|----------------|----------|
|Pegasus|No|No|No|
|Tempo|No|No|Yes|
|Turbo|Yes|No|No|
|Vaporfly|Yes|Yes|No|
|Alphafly|Yes|Yes|Yes|

```python
def categorize_nikes_running_shoes(has_zoomx: bool, has_carbon_plate: bool, has_airbag: bool) -> str:
    """
    >>> categorize_nikes_running_shoes(False, False, False)
    'Pegasus'
    >>> categorize_nikes_running_shoes(False, False, True)
    'Tempo'
    >>> categorize_nikes_running_shoes(True, False, False)
    'Turbo'
    >>> categorize_nikes_running_shoes(True, True, False)
    'Vaporfly'
    >>> categorize_nikes_running_shoes(True, True, True)
    'Alphafly'
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 10. Define a function `sing_do_re_mi()` which returns the lyrics of "Do-Re-Mi".

Source: <https://youtu.be/Qy9cj-zwbVY>

```python
def sing_do_re_mi(note: str) -> str:
    """
    >>> sing_do_re_mi("Do")
    'a deer, a female deer.'
    >>> sing_do_re_mi("Re")
    'a drop of golden sun.'
    >>> sing_do_re_mi("Mi")
    'a name I call myself.'
    >>> sing_do_re_mi("Fa")
    'a long long way to run.'
    >>> sing_do_re_mi("So")
    'a needle pulling thread.'
    >>> sing_do_re_mi("La")
    'a note to follow so.'
    >>> sing_do_re_mi("Ti")
    'a drink with jam and bread.'
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```