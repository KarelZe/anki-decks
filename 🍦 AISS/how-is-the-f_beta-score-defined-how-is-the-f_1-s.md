# Note
```
guid: nNU2Srrb3q
notetype: Basic-d7a3e-4ce08
```

### Tags
```
03_evaluation
repeat
```

## Front
How is the \(F_{\beta}\)-score defined. How is the \(F_1\) score defined? How is the \(F_{0.5}\) score defined? How is the \(F_{2}\) score defined?

## Back
\(\begin{aligned} F_{\beta}-\text { Score }
&:=\frac{\left(1+\beta^{2}\right) T P}{\left(1+\beta^{2}\right)
T P+\beta^{2} * F N+F P} \\ &=\left(1+\beta^{2}\right) *
\frac{\text { precision } * \text { recall }}{\left(\beta^{2} *
\text { precision }\right)+\text { recall }} \end{aligned}\)
<div>
  \(F_1=2 * \frac{\text { precision } * \text { recall }}{\text {
  precision }+\text { recall }}\)
</div>
<div>
  \(F_{0.5} = 1.25 * \frac{\text { precision } * \text { recall
  }}{0.25 * \text { precision }+\text { recall }}\)
</div>
<div>
  \(F_2 =5 * \frac{\text { precision } * \text { recall }}{4 *
  \text { precision }+\text { recall }}\)
</div>
