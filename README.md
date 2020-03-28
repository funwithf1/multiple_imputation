# multiple_imputation
Multiple Imputation in R

Rubin's rules
Example of multiple imputation with two variables

Simulating Data
```
#Generate data
x<-seq(1, 10)
error <- rnorm(10,0,1)
y<-1+ x + error

#Remove observations
n<-7
miss.col <-c(6,8,10)
x.obs<-x[-miss_col]
y.obs<-y[-miss_col]
```
