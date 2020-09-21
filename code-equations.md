# Example with both code and equations

Here's an example with both code and equations. Suppose you're using R, and you decide you want to estimate a linear regression model of the form
$$y_{t} = \alpha + \beta x_{t} + \gamma z_{t} + varepsilon_{t}$$

You can do that using the code

```
fit <- lm(y ~ x + z)
summary(fit)
```
