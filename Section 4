# HarvardX-PH125.2x

Excercise 1. Life expectancy vs fertility- Part 1
The Gapminder Foundation (www.gapminder.org) is a non profit organization based
in Sweden that promotes global development throught the use of statistics that
can help reduce misconceptions about global development.

library(dplyr)
library(ggplot2)
library(dslabs)
data(gapminder)

gapminder%>% filter(continent=="Africa" & year == 2012) %>%
              ggplot(aes(fertility,life_expectancy))+
              geom_point()
              
 
 Excercise 2. Life expectancy vs fertility- part 2- coloring your plot
 
 Note that there is quite a bit of variability in life epectancy and fertility with
 some African countries having very high life expectancies. There also appear to be
 three clusters in the plot.
 
 library(dplyr)
 library(ggplot2)
 library(dslabs)
 data(gapminder)
 gapminder%>%filter(continent=="Africa" & year==2012)%>%
              ggplot(aes(fertility, life_expectancy, color=region)+
              geom_point()
          
    
  Exercise 3. Life xpectancy vs fertility- part 3- selecting country and region
  While many of the countries in the high life expectancy/low fertility cluster are 
  from Northern Africa, three countries are not.
