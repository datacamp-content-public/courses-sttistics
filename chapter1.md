---
title: 'First chapter'
description: 'Some description'
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

Это начало большего конца! Все работает отлично! и все все! 

`@instructions`
Create a vector `temp` of values 1 through 30 and display it Работает???

`@hint`


`@pre_exercise_code`
```{r}
# create temp 1:30 а здесь?

# print temp
```

`@sample_code`
```{r}
temp <-    # здесь
```

`@solution`
```{r}
temp <- 1:30
temp
```

`@sct`
```{r}
test_object("temp")
test_output_contains("temp", incorrect_msg = "Make sure to print `a`.")
success_msg("You are my hero")
```
