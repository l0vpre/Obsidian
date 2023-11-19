Ключевое слово `typedef` используется для объявления псевдонимов [[Типы данных|типов]].
Например, конструкция ниже создаст псевдоним `size_type` для типа `unsigned long long`: 
```c
typedef unsigned long long size_type;
```

### Структуры с Typedef
`typedef` часто используется для объявления псевдонима [[Структуры|структуры]].

Без `typedef`:
```c
struct Point{
    float x;
    float y;
};

struct Point a;
```

С `typedef`:
```c
typedef struct {
    float x;
    float y;
} Point;

Point a;
```
