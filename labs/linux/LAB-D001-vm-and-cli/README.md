# LAB - D001 - VM and CLI Foundations (Ubuntu on Virtualbox)

##LAB 1##

## Goal:
- Setup Github repo locally inside Ubuntu and create snapshot for easy recovery for future.

## Success Criteria (must be true)
- Can run `ls` and see your repo folder inside ~/projects
- Repo contains the folders notes/, labs/, runbooks/, scripts/, diagrams/, and ADRs/.
- A VM snapshot named Fresh Install has been created

### Evidence Blocks

## Evidence #1 - Make sure projects folder exists

# Command

bash


fayaadhw@fayaadhw-VirtualBox:~/projects/cloud-roadmap-portfolio$ cd ~/projects
fayaadhw@fayaadhw-VirtualBox:~/projects$ pwd



# Output


/home/fayaadhw/projects


# What this proves

- This proves that there is a subfolder within my main directory named projects


## Evidence #2 - Clone Github repo onto Ubuntu

# Click path

-Copy the HTTPS clone URL from Github

# Command

bash

git clone https://github.com/abdulffw/cloud-roadmap-portfolio.git

cd cloud-roadmap-portfolio


# Output

fayaadhw@fayaadhw-VirtualBox:~/projects/cloud-roadmap-portfolio

# What this proves

- This shows that my Github repo is now cloned onto Ubuntu and i have access to my repo on Ubuntu


## Evidence #3 ## - VM Snapshot is created

# Click path

- VirtualBox Manager -> select VM -> Snapshots -> Take

# Snapshot Name

- Tools Installed

# Snapshot Description

- Fresh install + basic tools installed

# Date/Time created

-Mon Jan 12 07:24:47 PM EST 2026

## Evidence #4 ## - run `pwd`

# Command

bash

pwd

# Output

/home/fayaadhw/projects/cloud-roadmap-portfolio

# What this proves

- shows which directory i am currently in, in my case i am in my repository


## Evidence #5 ## - run `ls`

# Command

bash

ls

# Output

ADRs  diagrams  evidence  labs  notes  README.md  runbooks  scripts  templates

# What this proves

- shows the file/folder structure within my repo, shows which files and folders exist in my directory


## Evidence #6 ## - run `git status`

# Command

bash

git status

# Output

On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   README.md
	modified:   notes/W01/Day01-os-linux-vm.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	notes/DayXXX-Notes-Template.md
	notes/W01/.Day01-os-linux-vm.md.swp

no changes added to commit (use "git add" and/or "git commit -a")

# What this proves

- shows that i am in a real Git repo, in my case i am in cloud-roadmap-portfolio




## LAB 2 ##

## Goal:

- Become comfortable moving around Linux and creating/editing files using the terminal

## Success Criteria (must be true)

- `pwd` shows you are inside ~/sandbox/day01
- `cat hello.txt` displayed the sentence you typed(before deleting)
- your `notes/` folder exists and contains `hello-renamed.txt`

# Evidence #1 - `pwd` shows where i am in my directory

# Command

bash

mkdir -p ~/sandbox/day01

pwd

# Output

/home/fayaadhw/sandbox/day01

# What this proves

- this shows where i am currently in my directory and in my case i am in the day01 folder

# Evidence #2 - show list of folders including hidden

# Command

bash

ls -la

# Output

total 8
drwxrwxr-x 2 fayaadhw fayaadhw 4096 Jan 12 20:08 .
drwxrwxr-x 3 fayaadhw fayaadhw 4096 Jan 12 20:08 ..

# What this proves

- This shows all the folders within my current directory including any hidden folders

# Evidence #3 - run `cat` to display text in hello.txt

# Command

bash

cat hello.txt

# Outcome

Day 1: I am learning Linux.

# What this proves?

- This shows the content of the file I chose, for my case I used the cat on the text file hello.txt and it showed: Day 1: I am learning Linux.


# Evidence #4 - Notes folder exists and contains the file hello-renamed.txt

# Command

bash

cd notes

ls -la

# Output

total 12
drwxrwxr-x 2 fayaadhw fayaadhw 4096 Jan 12 20:26 .
drwxrwxr-x 3 fayaadhw fayaadhw 4096 Jan 12 20:26 ..
-rw-rw-r-- 1 fayaadhw fayaadhw   28 Jan 12 20:24 hello-renamed.txt

# What this proves?

- This shows that the file hello-renamed exists within the folder notes


## CLI File Ops Evidence ##

# Output for pwd
/home/fayaadhw/sandbox/day01/notes
# Output for ls
hello-renamed.txt
# Output for cat 
(empty)
