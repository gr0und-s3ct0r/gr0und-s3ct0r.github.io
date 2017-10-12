---
layout: post
title:  "How to contribute to ansible project"
date:   2016-12-6 12:55:28 +0100
categories: ansible contribute version git fork bug report
---
## Introduction

Because we find Ansible, just awsome, we would like to share our experience about contributing on it. 
We will see, step-by-step, how to contribute on Ansible and generally on a lot of open-source projects. 
We so will begin it by refreshing you on what is Ansible. 
Next we will see four steps, how to set-up your environment, how to develop on it, how to perform your first pull-request and then we will se the best process to have your request accepted. 

## Goals

The goal of this article is, of course, how to become an Ansible contributor, but not only, we will help you to speed up your pull-request merge! 

Ansible is needing help, and of course everyone are welcome! Let's begin!

## Prerequisites
Contribute on Ansible implies some prerequisites.

Ansible is written in python so you'll need different versions to ensure compatibility:
- python 2.7
- python 3.5

To improve development lifecycle we will use [pipenv](https://github.com/kennethreitz/pipenv).
Instead, you can use mainstream tools like `virtualenv` and `pip`.

Ansible project is hosted on github so [you require a github account](https://github.com/) for deal with it.

Github is based on the `git` version control system, so you'll need it.

You'll need also [docker](https://www.docker.com/) to have a fully isolated development setup to play your playbooks against.
Ansible unit and integration tests have parts also based on docker.
For your information, this is a very interesting part to contribute on Ansible.

## What's Ansible?
    Principe de fonctionnement
    petit exemple d'installation d'un paquet (liens vers le site officiel de ansible)
    Différencier serveur de client (machine hote ou cible) retrouve rles vrais termes ansible

## Why contribute?

Ansible usage have grew up rapidly and many issues are continously opened.

An issue can be a feature request, a bug reporting, or even simply a question to the maintainance team.
Rather than considering, ansible need contributors to continue to improve its quality and stability every days..

The big parts of contributors are volunteers and workss on ansible on free times.
The rest of the contributors are considered as commiters, they are members of the core team.

You can contribute by adding parts of documentation, migrate code, fix issues or even adding features.
So all contributions are welcomes!

Contributing helps you to improve your skill about ansible but also improve your
skills on large distribued development team all around the world.

You would become more efficient with git usages, concepts, and a lot of stuffs very useful in the real life.

Working on this project allowed us to discover it in depth. We discovered new uses, new modules, and a lot of nice things.

## Step 1 - Prepare environment
    a. Récupérer les sources
        . Forker le projet
        . checkouter en local
        . configurer l'upstream (avec comment update le fork)
        . se placer sur la bonne branche

    b. Créer un environnement python (pyvenv)
    c. Créer des hotes à configurer (docker)

## Step 2 - Take action!
    a. find issue on ansible
    b. apply coding best practices
    http://docs.ansible.com/ansible/latest/community.html#for-current-and-prospective-developers
    c. test
    http://docs.ansible.com/ansible/latest/dev_guide/testing.html
    d. Git : rebase, cherry-pick, squash, --amend
    e. push on your github repository

## Step 3 - Make a pull request
    a . create PR in github
    b. understand ansibullbot labels

## step 4 - What's happens next?
    a. How to integrate modifications to the PR
    b. obtain 2 shipit

    Git
    Github

## Conclusion
