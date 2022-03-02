summary (trees$Girth)

summary(iris)
library(EnvStats)
lapply(iris, skewness)

rbind (sd=lapply(iris[1:4], sd), 
       sk=lapply(iris[1:4], skewness))

#same results:
summary(iris[iris$Species == 'setosa', ])
with(iris, summary(iris[Species == 'setosa', ]))

with(iris, lapply(iris[Species == 'setosa', ], kurtosis))


iris.setosa <- subset(iris, subset= (Species=='setosa'),
                      select = c(Sepal.Width, Sepal.Length, Petal.Width, Petal.Length))
lapply(iris.setosa, mean)


aggregate(iris[1:4], by=list(iris$Species),mean)
