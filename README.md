# Going fishing with my Raspberry PI

From June 28, 2020, to August 3, 2020, I recorded more than ssh 3K sessions from all over the world.

To accomplish this, all I had to do was to expose a raspberry pi through my router’s DMZ running cowrie, “a medium to high interaction SSH designed to log brute force attacks and the shell interaction performed by the attacker”.

Sessions contained all kinds of ssh interactions: trojans, rootkits, and even friendly hello messages.

I also stored more than 1 week of network traffic, our little raspberry PI interacted with more than 8000 IP addresses.

My mission in this paper is to analyze thread data, including network data, session logs, and how honeypots can be leveraged to understand threads. I will also propose some mitigation strategies that could be implemented at the ssh server and OS levels.

## YouTube Video
[YouTube](https://youtu.be/hyOI3fzEY6I)

## Paper
[Paper](going_fishing_raspberry_pi.pdf)
