---
layout: post
title: Code Snippets
description: Post about code snippets
---

You can use color-coded code-snippets with the normal Markdown syntax.

````python
from typing import List


def fizz_buzz(n: int) -> List[str]:
    result: List[str] = []
    for i in range(1, n + 1):
        entry = ""
        if i % 3 == 0:
            entry += "Fizz"
        if i % 5 == 0:
            entry += "Buzz"
        if entry:
            result.append(entry)
        else:
            result.append(str(i))
    return result


limit = int(input("Please enter the limit for the fizz buzz list (1-n)\n: "))
print(fizz_buzz(limit))
````
