# Ak-s-intro-To-Arithmetics-on-Rstudio

Basic arithmetics syntax : 
## Vectors

```{r}
vector <- c(1,2,3,4,5)
```

## Mean
Mean is basically average.

```{r}
vector <- c(1,2,3,4,5)
mean(vector)
```

## Strings
We learnt that vectors can hold strings

```{r}
String <- c("Akshat", "Nodnat", "Tahska")
```

## Plot
Below is an example of scatter plot

```{r}
age <- c(13, 13, 16, 16, 11.5, 11, 8)
weight <- c(48, 60, 50, 32, 34, 28,  48)
plot(x=age,y=weight, main="Age Group", xlab = "Age", 
     ylab = "Weight", pch=19, col="red")
```

## Matrix
Below is an example of a basic matric. A matrix is basically a double array.
```{r}
mat.Akshat = matrix(1:8, 2, 4)
dim(mat.Akshat)
```

## Histograms
Below we can find the codes we need to graph a histogram. 

```{r}
hist(c(4:25),5)
```
