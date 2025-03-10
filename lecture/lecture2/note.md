

# analyze the time of algorithm
### techniques

### Telescoping Method

The telescoping method is a mathematical technique often used to simplify sums or series. It works by expressing a sum in such a way that most terms cancel out, leaving only a few remaining terms. This technique is particularly useful when dealing with series where each term is a difference between two expressions.

#### Example

Consider the series:
\[
S = \sum_{n=1}^{N} \left( \frac{1}{n} - \frac{1}{n+1} \right)
\]

Using the telescoping method, the terms of the series expand as follows:

\[
S = \left( \frac{1}{1} - \frac{1}{2} \right) + \left( \frac{1}{2} - \frac{1}{3} \right) + \left( \frac{1}{3} - \frac{1}{4} \right) + \cdots + \left( \frac{1}{N} - \frac{1}{N+1} \right)
\]

As you can see, most of the intermediate terms cancel out:

\[
S = 1 - \frac{1}{N+1}
\]

The result of the series is simply:
\[
S = 1 - \frac{1}{N+1}
\]

### Key Points:
- The telescoping method involves breaking a series into differences that cancel out.
- It is most effective when the sum has terms that are naturally of the form \( (a_n - a_{n+1}) \).
- The method simplifies the evaluation of sums by reducing the number of terms that remain.


### substitution method

