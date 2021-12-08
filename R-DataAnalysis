#  Reading the file
test <- read.csv("Sample_data.csv", header = TRUE)

#uploading libraries
install.packages("modeest")
library(modeest)

#Exploring the data
str(test)
head(test)
summary(test)


#Measure of Central Tendency
mean(test$Age) #mean
median(test$Age) #median
mlv(test$Age) #mode

#Measure of dispersion
range(test$Age) #range
var(test$Age) #variance
sd(test$Age) #standard deviation
IQR(test$Age) #IQR
mad(test$Age) #MAD

#data visualizations
hist(test$Age, col = 'steelblue', main = 'Histogram of the ages of respondents',
     xlab = 'Respondents Age') #histogram
plot(density(test$Age), main = 'Density plot of the ages of respondents',
     xlab = 'Respondents Age') #density plot
qqnorm(test$Age);qqline(test$Age) #Q-Q plot and line
boxplot(test$Age, main = 'Boxplot of the ages of respondents',
        xlab = 'Respondents Age') #boxplot
