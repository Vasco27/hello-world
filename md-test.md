Hello, my name is __Vasco__.

Can we make a TOC?[^9f14]

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Introduction](#introduction)
	- [Development](#development)
- [What about code blocks](#what-about-code-blocks)
	- [Code blocks](#code-blocks)
		- [Python code block](#python-code-block)
		- [Bash code block](#bash-code-block)

<!-- /TOC -->

# Introduction

I'm a _software engineer_ and I enjoy markdown.

## Development

Here, I will test the creation of a new table.

Fruta | Comida  | Bebida
------|---------|----------
Maçã  | Picanha | Sumol
Pera  | Dourada | Coca-cola

Nice looking table

# What about code blocks

I hope it works.

## Code blocks

A collection of code blocks

### Python code block

A nice python code block.

```python
import pandas as pd

pd.read_csv("my_file.csv", index=True)

pd.hist()

l = []
i = 0
for l in range(3):
  l.append(i)
  i = 1+1
```

The color scheme looks good.

### Bash code block

```Bash
cd Desktop

ls -la

conda env create --name conda-env python=3.6
conda activate conda-env

python run_backend.py
```

[^9f14]: new footnote
