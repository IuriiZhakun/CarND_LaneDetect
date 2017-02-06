Hi, 

I tried to use k-means clustering to find a group of lines which have similar slope and position.
In addition I filtered groups of lines by length and covered area.
I applied (tiny) ema smoothing on line coefficients.
Because a physical road cant turn or change direction too sharp.

My current algorithm will fail on sharp turns, because it searches for a direct line (kx+b).
Also there are issues with detecting lines on bright background.
Also there might be false positives, like a shadow from a truck.
So adding constraints as to what minimal lane should be looks like a good idea.

Please check the challenge results.

Regards,
Iurii
