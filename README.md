# using-cat-and-awk-commands-in-unix-to-play-with-files


![image](https://user-images.githubusercontent.com/124582454/218749243-18f5a5f0-852a-490a-907e-6448ea344f38.png)

command :
```
 cat EQ_2022_Country.csv | awk -F"," '{print  "(""\""$1"\""",""\""$2"\"""A)"}'
 ```
