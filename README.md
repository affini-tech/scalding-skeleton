Description
---
This project is a simple scalding example using a "Fat Jar". The code is the reproduction/adaption of the Example3 of part 8 of the tutorial "Cascading for the Impatient" (https://github.com/Cascading/Impatient/tree/master/part8). It's intented to be used as a skeleton to build a "Fat Jar" scalding application.

Use
---

    mvn clean package
    
    hadoop jar target/fatjar-1.0.0.jar WordCount --hdfs --doc data/rain.txt --wc output_fatjar.tsv
