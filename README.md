# Trivially!

A simple latex class to avoid saying trivially. Package inspired and list shamelessly stolen from [\r\math](https://www.reddit.com/r/math/comments/7gqhlc/what_to_say_instead_of_trivially/). To use simply download the .sty file and drop it into the same folder as your latex source file, add
```latex
\usepackage{trivially}
```
to your preamble and whenever you want to say to say trivial instead invoke
```latex
\trivial
```
which will pick one of the 243 equivalent statements at random for you. If you know the index of one you particularly like you can also use
```latex
\trivial[i]
```
where i is the index of the trivially synonym.
