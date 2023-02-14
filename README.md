# using-cat-and-awk-commands-in-unix-to-play-with-files


![image](https://user-images.githubusercontent.com/124582454/218749243-18f5a5f0-852a-490a-907e-6448ea344f38.png)

command :
```
 cat EQ_2022_Country.csv | awk -F"," '{print  "(""\""$1"\""",""\""$2"\"""A)"}'
 ```

![image](https://user-images.githubusercontent.com/124582454/218750307-ec8d30fd-7f43-4d62-b65f-a10aed7638a7.png)

we can use the "head" command to print the first n number of line in the file


![image](https://user-images.githubusercontent.com/124582454/218750944-9dd8a121-3a82-4204-8787-04520436f54d.png)
