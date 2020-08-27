# satysfi-matrixcd

`matrixcd` is a SATySFi package for drawing commutative diagram with a syntax similar to tikz-cd (LaTeX package)

## Example
```
\eqn(${
  \MatrixCD.matrixcd!(open MatrixCD in {
    | ${A}\arrow[to `rd`];  | ${B} \arrow[to `l`;label ?:[swap;description] {${f}};dotted]; \cr;
    |  | ${C}\arrow[to `u`; label {${g}}; mapsto];
  |})
});
```

