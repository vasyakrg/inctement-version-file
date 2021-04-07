# Скрипт хук, инкрементирующий файл версий

- на вход принимает имя файла с версией приложения
- версия должна быть в формате `X.Y.Z,` где `X` - любой число от `0` до `бесконечности`, `Y` и `Z` - числа от `0` до `9` включительно
- хук увеличивает число `Z` на `единицу`, пока оно не станет больше `9ти`, потом он выставляет `Z` на `0`, а число `Y` увеличивает на `единицу`
- и так же с `X`, когда `Y` станет больше `9`
- `X` не ограничивается деватью и растет постоянно

## Пример запуска

```
./version-hook.sh VERSION
```

# Script hook that increments the version file

- accepts the name of the file with the application version as input
- version must be in the format `X.Y.Z,` where `X` - any number from `0` to `infinity`,`Y` and `Z` - numbers from `0` to `9` inclusive
- the hook increases the number `Z` by `one` until it becomes more than `9`, then it sets `Z` to `0`, and the number `Y` increases by `one`
- and so with `X` when `Y` becomes greater than `9`
- `X` is not limited to nine and grows constantly

## Example execute

```
./version-hook.sh VERSION
```


## Автор \ Author

- **Vassiliy Yegorov** [vasyakrg](https://github.com/vasyakrg)
- [youtube](https://youtube.com/realmanual)
- [site](https://vk.com/realmanual)
- [telegram](https://t.me/realmanual)
- [any qiestions for my](https://t.me/realmanual_group)
