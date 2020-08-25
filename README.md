# HW3


Please use D2L to turn in both the HTML/DOC/PDF output and your R Markdown file in.

## Q1. R style guide (2 pts)
Summarize what you learned from the [Hadley Wickham's Style Guide](http://adv-r.had.co.nz/Style.html).

## Q2. Course Overview (2 pts)

### a. (1 pt) 
What has been your favorite thing about this course so far?

### b. (1 pt) 
What (if anything) could be changed in this course to improve your learning?



## Q3. Creating Tables (2 pts)

Download the Housing dataset at: [http://math.montana.edu/ahoegh/teaching/stat408/datasets/HousingSales.csv](http://math.montana.edu/ahoegh/teaching/stat408/datasets/HousingSales.csv). Compute the average home price across the states in the dataset. Print the results to a table using the `kable` function.

Also write a sentence that describes the average housing price in Montana and use R Markdown's inline tools to include the price in a sentence.

## Q4. 
Evaluate the following R code and provide a written explanation about what each piece of code does.

```
ski <- data.frame(ski.hill = c('Bridger Bowl','Big Sky','Red Lodge Mtn'), 
                  new.snow = c(TRUE,FALSE,TRUE),
                  acres = c(2000, 5800, 1600 ))
```

### a. (1 point)
```
ski[1, 1]
```
 
 
### b. (1 point)
```
subset(ski, new.snow == TRUE)
```


### c. (1 point)
```
max(ski$acres)
```

