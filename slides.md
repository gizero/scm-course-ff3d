# Put a nice title here

### Andrea Galbusera (gizero)

- gizero@gmail.com
- [@gizero76](https://twitter.com/gizero76)
- [GitHub](https://github.com/gizero)

---

# The Speaker

embedded systems designer/architect

spare time full-stack web developer

doing SCM since 2002 (in some way teaching it)

using `git` since 2010

doing research into SCM technologies and best practices

---

# Agenda

## Day 1
- disclaimer
- what's this all about?
- (brief) history of SCM

--->

# Agenda

## Day 2
- workshop

---

# Disclaimers

- work in progress teaching experiment
<!-- .element: class="fragment" data-fragment-index="1" -->

- many concept are tool agnostic...
<!-- .element: class="fragment" data-fragment-index="2" -->

- ...but this is about `git`
<!-- .element: class="fragment" data-fragment-index="3" -->

- client agnostic
<!-- .element: class="fragment" data-fragment-index="4" -->

- ...but heavily biased towards command line (will tell you why)
<!-- .element: class="fragment" data-fragment-index="5" -->

---

# In This Course We Will

- talk interactively to each other
- sketch some diagrams
- ...
- build a reasonable work flow strategy

---

# Then...

- you will learn the commands to implement it

Note: invece di concentrarsi sui comandi ci focalizzeremo maggiormente sul
perchè vogliamo fare qualcosa e poi su come implementarla. Useremo i
diagrammi per stimolare gli stessi processi di apprendimento che normalmente
portano alcuni di noi a preferire le GUI rispetto alle interfacce CLI.

---

# Vocabulary

- Source Control
- Version Control
- Revision Control
- Source Code Management

Note: con il termine SCM comprendiamo anche pratiche e strumenti più o meno
correlati con il controllo di revisione, quali il deployment e il ticket/issue
tracking

Note: quindi vediamo cosa ci permettono di fare questi strumenti che rientrano
nella classificazione appena introdotta...

---

- keep track of changes over time
- backup older files
- work with others on a project simultaneously
- keep track of authorship

---

- big (or even small) change breaking things

---

- move things from one host to another

---

# working solo?

- productivity tool
- easily switch between tasks
  + paralelizing activities
- quickly react to urgencies
  + make a quick fix while working on a new feature

---

# working in team?

- don't step on each other's feet
- minimize coordination overhead
- reduce onboarding costs for new resources
- leverage and improve team skills with peer review

---

# do I really need a tool? (alternatives)

- frequently backup your files (caveman SCM)

PROs:
- straightforward: anyone knows how to do it

CONs:
- what does frequently mean?
- how to deal backups with (housekeeping)
- find useful things among backups

---

# Distributed vs Centralized

- Centralized VCSs:
  + CVS
  + SVN
  + TFS

- Distributed VCSs:
  + Mercurial
  + BitKeeper
  + git

---

# Authorship

- VCS keep track of "who made what"
- allow "blaming" changesets

---

# Exercise 1: 
---

# Workflows

---

# Interlude - VCS and the ecosystem
- ticket driven development (issue tracking)
- QA (testing strategies)
- deployment strategies

---

# Scheduled Deployment
- ticket based development

---

# Continuous Deployment
- either a solo developer workflow or a more mature "trust your code" thing

---

# Why the command line interface

It's a matter of taste but:
- as a programmer I don't trust GUIs
- it's eleganct (clicking here and there becomes boring)
- allows progressively replacing yourself with scripts (automation)
- easier to write cheat sheets, share knowledge and ask the web for help (Stack Overflow)


# Slide 3

    $ git init .

<!-- .element: class="fragment" data-fragment-index="1" -->

    $ git add .

<!-- .element: class="fragment" data-fragment-index="2" -->

    $ git commit .

<!-- .element: class="fragment" data-fragment-index="3" -->
