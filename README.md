# ansible-devenv

I frequently rebuild my development environment for all kinds of reasons. It's often simply the
best way to get rid of the cruft. I know my way around, but invariably, everytime I do it, there's
a couple of "little things" I forget and they're a pain to set up again, mostly because I forgot the
context of those little things.

To solidify my "devenv" situation, I'm automating its setup with this repo. The goal is not to
automate my whole system's setup, but rather to automate the tricky/repetitive parts.

It's designed to run on a Gentoo env (can be a freshly installed one) with Ansible installed.
