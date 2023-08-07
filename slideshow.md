---
marp: true
---

# Intro to Linux
Cormac Sharkey

---

## Who am I?
- UCC goblin & wheel person
- UWA graduate
- Professional computer wrangler
- Bird enthusiast
- github.com/bir-d

---

## What is Linux?
- A kernel
- Not necessarily an OS
- But a major building block towards one
![alt](./images/Kernel_Layout.svg) *A little bit like this!*
###### Bobbo, CC BY-SA 3.0 <https://creativecommons.org/licenses/by-sa/3.0>, via Wikimedia Commons

---

## Why does this matter?

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

## The main takeaway
Pretty much *everything* is just a bunch of smaller programs stuck together
![w:auto h:500](./images/litter%20of%20processes.png)(I wish it was this nice...)

---

## Let's talk more about the shell
![alt](./images/shell.png) (this thing)

---

## Let's talk more about the shell
- (yet another) program
- Also known as a "command line" or "terminal"
- Multiple available
    - The most popular of which is `bash`
- What is this useful for?
    - Running more programs of course!
    - Let's go run one

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
1. Figure out what your problem is
2. Figure out what program you need to care about
3. Look it up lol

---

## An easy example

![alt](./images/simpleproblem.png) (`file` just prints out the file type of it's argument)

---

## An easy example

1. Figure out what your problem is
![alt](./images/simpleproblems1.png)

---

## An easy example
2. Figure out what program you need to care about
