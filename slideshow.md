---
marp: true
---

# Intro to Linux
Cormac Sharkey

---

## Who am I?
- UCC committee/wheel person
- UWA graduate, soon to be professional computer wrangler
- github.com/bir-d

---

## What is Linux?
- A kernel
- Not necessarily an OS
- But a major building block towards one
![alt](./images/Kernel_Layout.svg) *A little bit like this!*
###### Bobbo, CC BY-SA 3.0 <https://creativecommons.org/licenses/by-sa/3.0>, via Wikimedia Commons

---

## So what are these "distros" I keep hearing about?
- A distro (distribution) is simply Linux + a bunch of other programs to help you get things done.
- For example, Ubuntu is Linux + a desktop environment (GNOME) + a bunch of other stuff.
- As a result....

---

## Linux
![alt](./images/mintcinnamon.png)

---

## (also) Linux
![alt](./images/archcraft.png)

---

## (I can't believe it's still) Linux
![alt](./images/Archterm.png)

---

## Archaic but effective
![alt](./images/Ubuntu%20with%20terminal.png)

---

## A reoccuring theme
Pretty much *everything* is just a bunch of smaller programs stuck together
![w:auto h:500](./images/litter%20of%20processes.png)(I wish it was this nice...)

---
## The key
**Understand which of these programs you care about and how to interact with them.**

---

## Let's talk more about the shell
![alt](./images/shell.png) (this thing)

---

## Why?

- We need some way to get stuff done on the computer, and
    - As we've seen, a graphical environment is *nice*, but **not guaranteed!**
        - Linux with no display manager or window manager installed is still Linux!
- However, the shell is typically always available -- and ubiquitous across every distro.
- The shell is also **VERY GOOD** at interacting with very specific programs -- in very specific ways.
---

## What is the shell?
- (yet another) program
- Also known as a "command line" or "terminal"
- Multiple available
    - The most popular of which is `bash`
      - It's worth noting that MacOS also uses this!
- Most often, this will be run on your own computer (local shell), or you will be interacting with a remote shell (via SSH)

--- 

## Commands...
![alt](./images/shellcommandannotated.png)

---

## Another one
![alt](./images/lsannotated.png)

---

## Introducing flags
![alt](./images/lsflagannotated.png)

---

## Introducing flags
Alters a programs *behaviour*
- ls
    - Prints all non-hidden files in the current directory
- ls **-l**
    - Prints all non-hidden files, as well as additional information.
- You can string these together
    - Try `ls -l -t -r -a -p`
        - shorter: `ls -ltrap`
- The manual page lists all of the flags (and more!) for any program with an entry
    - Try `man`, and pass it a programs name as its first argument! (`man ls`)

---

## Anatomy of a command
Essentially: name of program, any required *flags*, then as many required *arguments* as input
- You can then do all sorts of stuff with the output!
    - But this is a whole other can of worms (and might lead you down the evil path of becoming a sysadmin)

Common patterns?
- `program`
- `program` `FLAGS` `TARGET`
- `program` `FLAGS` `SOURCE` `DESTINATION`

---

## Teaching you how to fish
![alt](./images/Teaching%20Fishing.png)

---

## Teaching you how to fish
- Google is still your friend
- Finding out what to Google (and how to interpret the results) is the true challenge
- It will become easier with time and knowledge!
![alt](./images/googlemybeloved.gif)

---

## So lets go fishing!

- There are a few ways to go about getting started with Linux
- 