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

Анечка, здесь тебе нужно будет создать вектор `temp` и поместить в него значения от 1 до 10.

`@instructions`
Создать вектор, содержащий значения от 1 до 10.

`@hint`
Используй операцию среза (:)

`@pre_exercise_code`
```{r}
# Создай вектор `temp` и помести в него значения от 1 до 10.

# Выведи `temp`
```

`@sample_code`
```{r}
temp <-    # здесь
```

`@solution`
```{r}
temp <- 1:10
temp
```

`@sct`
```{r}
test_object("temp")
test_output_contains("temp", incorrect_msg = "Make sure to print `temp`.")
success_msg("You are my hero")
```
