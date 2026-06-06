MathJax Configuration

Default settings should be replaced.

AAT: Configuration Settings -> MathJax:
INLINE CONFIG:
`
{
  "extensions": ["tex2jax.js"],
  "jax": ["input/TeX", "output/HTML-CSS"],
  "tex2jax": {
    "inlineMath": [["\\(", "\\)"]],
    "displayMath": [["\\[", "\\]"]],
    "processEscapes": true
  }
}
`
