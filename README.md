# UOCIS322 - Project 0

Trivial project to exercise version control, turn-in, and other mechanisms
for CIS 322, introduction to software engineering at the University of Oregon.

## Before you begin

If you don't know how to SSH:

```
ssh your_cs_username@hostname
```

If you're using Windows, please refer to this [link](https://www.howtogeek.com/336775/how-to-enable-and-use-windows-10s-built-in-ssh-commands/) for instructions on enabling SSH in Windows.

An alternative for all platforms: [Termius](https://termius.com/).

In order to access your GitHub repos and commit changes from the server,
make sure you set up an SSH key first.
[Tutorial](https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).

When you're done, use the following command to add the key (do this every time you SSH into the server):
```
ssh-add path/to/.ssh/ssh_filename
```
If you're doing this locally (on your own device and not the server), and you're not using Linux, please pay attention to the Tutorial link above.

## Instructions

- Start by forking this repository on
[GitHub](https://github.com/alihassanijr/UOCIS322-P0),
then cloning onto the server. Read this file (`README.md`).

- Before you edit a file, read the comments (inside that file) carefully.

- Copy the `credentials-skel.ini` file, rename it to `credentials.ini` and fill in
  appropriately.

- Modify the program `hello.py` so that it prints "Hello
  world". (Nothing more and nothing less.)  Note that you do NOT do
  this by DIRECTLY adding the message to the `hello.py` source file.
  Rather, the message is a configuration constant from the `credentials.ini` file;
  fix it there.

- Replace these instructions with a proper README including the
   author, contact address, and a brief description of what the
   software does.

- Test your program locally; revise and re-test as needed. (How long
  can it take, really?)

- Commit your changes. You will need to use "git add" on your files
   `hello.py` and `README.md`, but *not* on `credentials.ini`, because that
   file does not belong on GitHub.  (In later projects it will contain
   confidential information, like access keys and passwords for web
   services.)  Your changes must be "pushed" to your public repository
   on GitHub so that the auto-checker can "clone" them back to the
   grading machine.

- Test your code with the `Makefile`. Use the command ``make run`` to execute.
Revise and push changes as needed.

- Turn in through Canvas. The file you turn in is `credentials.ini`. We
   use the repository link in your `credentials.ini` to access the rest,
   just like the auto-checker.



## Credits

Michal Young, Ram Durairajan, Steven Walton, Joe Istas.
