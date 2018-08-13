## ###To upload a csv file to spark

Prerequisites

You should find out what your "file Path" is.  Then create a  read and load on the csv file

You should make sure you have already download spark:

Download link: https://spark.apache.org/downloads.html

`val df = spark.read.format("csv").option("header", "true").load("/home/cookiemonster/Documents/summer.csv")`



To show your schema:

df.show()