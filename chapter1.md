---
title: 'First chapter'
description: 'Some description'
---

## Упражнение для Анечки

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

something is ehre and there and everyevewhere

`@instructions`
Create a vector of values 1 thourhg 10

`@hint`


`@pre_exercise_code`
```{r}
# Create vector 1:10

# Print temp
```

`@sample_code`
```{r}
temp <-    # here
```

`@solution`
```{r}
temp <- 1:10
temp
```

`@sct`
```{r}
ex() %>% check_object("temp") %>% check_equal()
success_msg("Nice work!")
```
