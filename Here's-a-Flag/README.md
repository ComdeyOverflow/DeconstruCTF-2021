# Here's-a-Flag
 Category: Web
 
 Points: 150
 
 Description: A quick teaser to get yourself ready for the challenges to come! Just look for/at the flag and perhaps try your hand at some frontend tomfoolery?
 
 Url:  http://very.uniquename.xyz:2086/
 
![CTF](https://github.com/ComdeyOverFlow/DeconstruCTF-2021/blob/main/Here's-a-Flag/images/Screenshot%20from%202021-10-02%2011-18-37.png)

# Examming Website

When We go to website, it was just normal. There is nothing interesting.

![CTF](https://github.com/ComdeyOverFlow/DeconstruCTF-2021/blob/main/Here's-a-Flag/images/Screenshot%20from%202021-10-02%2011-19-16.png)

So let look at the page's source code.

As you can see, we can see three interesting. They are `fake flag` and `index.js` and `styles.css`. So let look at all.

![CTF](https://github.com/ComdeyOverFlow/DeconstruCTF-2021/blob/main/Here's-a-Flag/images/Screenshot%20from%202021-10-02%2011-19-28.png)

If we look into `index.js` we can see base64 strings. Let decode it
![CTF](https://github.com/ComdeyOverFlow/DeconstruCTF-2021/blob/main/Here's-a-Flag/images/Screenshot%20from%202021-10-02%2011-20-42.png)

After decode the base64 strings, we got youtube video link.
![CTF](https://github.com/ComdeyOverFlow/DeconstruCTF-2021/blob/main/Here's-a-Flag/images/Screenshot%20from%202021-10-02%2011-20-50.png)

Lol. That was just troll. 😂
![CTF](https://github.com/ComdeyOverFlow/DeconstruCTF-2021/blob/main/Here's-a-Flag/images/Screenshot%20from%202021-10-02%2011-21-15.png)

So let look at the `styles.css`. In this file, you can see `ROT13` string. Cool! Let decode this.
![CTF](https://github.com/ComdeyOverFlow/DeconstruCTF-2021/blob/main/Here's-a-Flag/images/Screenshot%20from%202021-10-02%2011-21-42.png)

When we deocde it with `23` Amount, we got flag.
![CTF](https://github.com/ComdeyOverFlow/DeconstruCTF-2021/blob/main/Here's-a-Flag/images/Screenshot%20from%202021-10-02%2011-28-39.png)

# Summary
Easy Challenge but give us a reminder to check all files in next ctf website.

# Flag
dsc{welcome_to_deconstructf}

# Thanks For reading!
