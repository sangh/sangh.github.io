Getting Opera (the browser) to use a proxy on OS X
==================================================

On every other desktop/laptop platform (except OS X) Opera has a setting for a
proxy server.  On OS X it uses the system settings---and so does virtually
every other browser (except for SeaMonkey)!

I care because I need the system default browser to not use a proxy so I can
get to my job's internal resources.  They have a proxy set up if you need to
hit something on the internet at large (they do this so no one accidentally
goes to an internet site when they meant to go to an internal one, which is a
crappy security measure, but I don't get to decide that).

I used SeaMonkey for a long time as my second browser, when I wanted to hit
something external to work, but over time that slowed my laptop down _a lot_.
I wanted to use Opera because it has this nice feature where if you open it
with a lot of tabs but don't actually focus on any of them it'll stop (or not
start) most scripts or not load those tabs tabs at all (and Opera will also
display PDF files inline).

Anyway after much searching around and giving up a couple times I stumbled on a
solution to this, which is install an extension `SimpleProxy`, but any of them
should work.  This causes Opera to use the setting in the extension instead of
the system ones---yay!

I'm writing this because just maybe it'll be picked up by search engines and
found by someone else in the same situation.
