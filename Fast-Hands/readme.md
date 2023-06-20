# Fast Hands 50 points - Warmups - 1286 Solves - easy

You can capture the flag, but you gotta be fast!

## Solution

We get a website that has a button labeled "Capture The Flag". When clicked, it opens and then immediately closes a window. 

Upon inspecting the page source, it was discovered that the button has an `onclick` event that calls the `ctf()` function, which opens a file named capture_the_falg.html.
![Fast-Hands-1.png](/images/Fast-Hands-1.png)


Navigating to that page reveals that the flag is not visible. ![Fast-Hands-2.png](/images/Fast-Hands-2.png) 

However, by viewing the page source, the flag was found `flag80176cdf1547a9be54862df3568966b8}`
![Fast-Hands-3.png](/images/Fast-Hands-3.png)
