
# new function according to number 7 in the list
my_function <- function(x) {
  y = cos(x) - 7
  return(y)
}



#make a vector called "X"
x <- c(1:100)
class(x)

# defining y
y <- my_function(x)
y

# create a graph
plot(y ~ x)
![as7](https://user-images.githubusercontent.com/116167612/196701829-05c4f767-033b-40f9-bdc9-cdafe64772ba.png)
