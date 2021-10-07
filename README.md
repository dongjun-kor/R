# R
############################ 필요한 패키지 설치
install.packages("rJava")
library(rJava)
install.packages("wordcloud")
library(wordcloud)
install.packages('KoNLP') source("https://install-github.me/talgalili/installr") installr::install.java() library(KoNLP)
library("KoNLP")

install.packages("rJava")
source("https://install-github.me/talgalili/installr")
installr::install.java()
library(rJava)

install.packages('KoNLP')
source("https://install-github.me/talgalili/installr")
installr::install.java()
library(KoNLP)

install.packages("wordcloud2")
library(wordcloud2)
#################### 텍스트마이닝
SejongDic()
NIADic()
text1=read.table("C:/a/AR2.txt")
text1=read.csv("C:/a/A.csv") #데이터 불러오기
is(text2) #성분확인
tx1=text1

ta=cbind(tx1)
ta=paste(tx1)
str(ta) #구조확인
dim(tx1) #차원확인
tx2=extractNoun(ta)
tx3=unlist(tx2)
tx4=as.character(tx1)
useNIADic()
dtm=DocumentTermMatrix(tx1) #명사추출
text2=sort(table(tx3),decreasing = T,300) #300개 row 내림차순정렬 후 상위 300개 선정
wordcloud2(text2) #시각화
tx4=mergeMethods("장","장치")
mergeMethods("장","장치")
table(text2)
str()
a=c("jan","Feb","mar","Apr","May","Jun","Jul","Aug","sep","Oct","Nov","Dec")
getwd()
library(ggplot2)
plot(tx1,type="l")
boxplot(tx1,horizontal = T,break=1)
ggplot()
plot(text1)
a=data.frame("jan","Feb","mar","Apr","May","Jun","Jul","Aug","sep","Oct","Nov","Dec")
day.1=data.frame(tx1,a)
ggplot(data = day.1,aes(day.1$,day.1$tx1))
barplot(text1$day)
