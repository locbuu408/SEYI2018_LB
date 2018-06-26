1. The number 7 occurs 16 times in MyMatrix. I used length(which(MyMatrix == 7)) to determine this number.
2. To find the sum of each column, I used the apply(MyMatrix, 2, sum).
3. To find the product of each column, I used apply(MyMatrix,2,prod).
4. You would change every instance frm 10 to 12 by using the MyMatrix[which(MyMatrix==10)]<-12.
5. There are 33 values that are greater than 3 and less than 8. (length(which(MyMatrix>3 & MyMatrix<8)))
6. I changed the elements of column 12 into character and retained columns 1-11 as numeric by using Mydatafram[,12]<-as.character(Mydatafram[,12]).
7. Rows 1,3, and 4 have a sum higher than 70. (which(MyDataframe$V13==FALSE)
)
