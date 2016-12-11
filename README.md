# github-origin
Bash shell script to toggle the GitHub remote origin from HTTPS to SSH and vice versa.

The best use case for this is to switch from HTTPS to SSH to avoid being prompted for a
password during a push to GitHub when you already have an SSH key added to your account.

## Installation
```
$ git clone https://github.com/uberhacker/github-origin
$ cd github-origin
$ chmod +x github-origin
$ sudo cp github-origin /usr/local/bin
```
## Usage
```
$ cd /path/to/github/repo
$ github-origin
```
