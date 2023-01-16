# maasccp

This is a reference implementation of the Canonical MAAS product in the C++ programming language.  A few important things about this code:

1. It is intended to help me (and others) learn the deep software architecture of MAAS, and understand the MAAS theory of operation, via the process of porting the code to another language.

2. I am trying to reproduce the core functionality of MAAS, not the Webapp (and Django, etc.) that goes with it.  This isn't going to be a 1-to-1 port of MAAS, but I want it to be a 1-to-1 port of the daemons that run MAAS.

Essentially, I just want to understand how the core daemons communicate and interact to do what MAAS does.  Since I'm not familiar with Django or Twisted -- which are big parts of the high-level functionality of this code -- this may take me some time to peel all that off. That's okay: it's not a race.  If I have to learn something about Django and Twisted along the way?  Hey, that's a bonus.

3. This is strictly an educational tool.  It isn't warranted for any particular operational use or purpose, so don't expect it to be a C++ replacement for MAAS.  That isn't a goal of this project, so if you try to use it for your particular application, caveat emptor: You deserve any breakage you experience, and I make no guarantee of fixing any bugs you may find.

That said, on with the code.

