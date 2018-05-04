# Instructions for the reproducibility project

This repo contains instructions for the students about git usage and projects update.

## Project description

The aim of current project is to learn python for computational biology through reproducing of some images from recent papers.
We encourage the students of the Faculty of Bioengineering and Bioinformatics, MSU, to share their results and code at Github.

The instructors of Python course at FBB selected a set of recent papers in top journals that students may reproduce. 
Reproducibility of each paper is supervised by the instructor, who does not contribute to the code. 
One paper is supervised by a team of students.

## GitHub instructions for students

1. Sign up to GitHub. Go to [Reproducibility organisation](https://github.com/Reproducibility-FBB-MSU) and request access to it. You might need to wait for the admins' response.

2. Install git on your computer with code for your project. For example, you can use conda: 

```
conda install git
```

3. Go to an empty directory. Clone your project to this folder. Example for terminal: 

```git clone https://github.com/Reproducibility-FBB-MSU/instructions.git```

4. Go to the created directory with project. Let's create your first commit. For example, add your name to the README.md to the list of contributors. Open README.md in any text editor and add your name to the list of contibutors (add this section is absent). Use [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) to get acquainted with markup basics. Save your changes. 

Add changed file, commit and push changes:

```
git add README.md
git commit -m "Student's introduction"
git push
```

## TODO list for instructors

1. Add more thorough walkthrough for students (e.g. addition of ssh key).

2. Add policy description (code should be commented and readable, etc.)
