---
title: "Hola Mundo en Python"
description: "Múltiples formas de imprimir un Hola Mundo en Python."
summary: ""
date: 2023-09-07T16:04:48+02:00
lastmod: 2023-09-07T16:04:48+02:00
draft: false
weight: 810
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---

Podemos escribir un **Hola Mundo** en ```Python``` de muchas formas.

¿Se te ocurre algúna nueva?

### Method 1
```python
print("Hello world")
```

### Method 2
```python
print('Hello' + 'world')
```

### Method 3
```python
print('Hello' + 'world')
```

### Method 4
```python
print('Hello', 'world')
```

### Method 5
```python
print('{} {}'.format('Hello','world'))
```

### Method 6
```python
word1 = 'Hello'
word2 = 'World¡
print(f'{word1} {word2})
```

### Method 7
```python
a = "!dlrow olleH"
b = a[::-1]
print(b)
```

### Method 8
```python
str = "!dlrow olleH"
print(''.join(reversed(str)))
```

### Method 9
```python
def greeting():
    print("Hello world!")

if __name__ == "__main__":
    greeting()
```

### Method 10
```python
while True: print('Hello world'); break
```

