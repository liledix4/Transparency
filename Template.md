Use this regular expression to replace placeholders with the values you need:

```regexp
(?<!`)\{\{[^\}]*\}\}(?!`)
```

# liledix4 Transparency – Work Week {{NUMBER}}

*<sup>{{DATE}}</sup>*

The easiest way to track progress without waiting for the next report dropping – [2do project!](https://github.com/users/liledix4/projects/15/views/3) It's updated in real time!

However, If you prefer the weekly digest, keep reading.

## Stats

These numbers are the sum of the values across all projects – including those not publicly available.

| Title                 | Value         |
| :-------------------- | ------------: |
| Lines of text added   | `+{{NUMBER}}` |
| Lines of text removed | `-{{NUMBER}}` |

[The term “lines of code” is controversial](https://en.wikipedia.org/wiki/Source_lines_of_code#Measurement_methods), so “lines of text” is used instead.

The count is done by summing up the numbers from all Git repositories on my computer.