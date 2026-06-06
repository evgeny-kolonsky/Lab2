#MathJax Configuration

Default settings should be replaced.

AAT: Configuration Settings -> MathJax:

1. Field **Inline Config**:
```json
{
  "extensions": ["tex2jax.js"],
  "jax": ["input/TeX", "output/HTML-CSS"],
  "tex2jax": {
    "inlineMath": [["\\(", "\\)"]],
    "displayMath": [["\\[", "\\]"]],
    "processEscapes": true
  }
}
```

2. Field **Source (_src)**:
```
https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.2/MathJax.js?config=TeX-MML-AM_CHTML
```
