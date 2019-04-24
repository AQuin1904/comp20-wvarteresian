# Comp 20
# Spring 2019
# Assignment 4: Security and Privacy Assessment for the Private Car Service
# William Varteresian

## Implemented
- Succeeded in obtaining data from partner's database without correct username or other credentials.
- Successfully identified multiple bugs / coding practice issues.

## Challenges
- I struggled to find my way around the suggested proxies and eventually gave up. I could not see the brief demonstration of their use in class because I can't read normal-sized text on the projector. (I want to get my prescription checked, but an eye exam means giving up a day to having my pupils dilated, which I can't afford right now.)
- Curl never works quite how other people assure me it should. It automatically escapes some quotation marks in strings sent as part of POST requests using --data. In office hours, it was suggested that I instead try "curl -i --data [URL]?[data to be sent];", but that just returned errors because curl thought there was no URL. I eventually gave up and went with what I could get.
- Finding issues that crashed the server required waiting for my partner to restart it.
- I attempted to launch CSRF attacks using JSFiddle, but I couldn't figure out how to manage the actual "attack" part, so all I got were a bunch of broken image links.
- I think I'm just not very good at all of these hacking things.

## Hours Spent
Eight to ten. Most of it spent trying and failing to troubleshoot software.