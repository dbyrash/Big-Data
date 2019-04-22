# Big-Data
## top 100 frequent words from 32GB text file. 

 ### -Created an efficient code using best practices of coding and Datastructures,  that runs Big data file, in short amount of time, has time and space complexity of O(n). 
 ### -Split the file before using it using a bash command in your linux system: 
  ### split -l$((`wc -l < data_32GB.txt`/32)) data_32GB.txt data_32GB.split.log -da 4
