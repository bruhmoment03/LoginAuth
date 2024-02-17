<h1 align="center">
LoginAuth
<img src="https://img.shields.io/badge/Made_by-s-yellow" />
<img src="https://img.shields.io/badge/language-C%2B%2B-%23f34b7d.svg" />
<img src="https://img.shields.io/badge/platform-Windows-blue" />
</h1>

## What's this?
LoginAuth written in C++ for finals (the actual homework I've handed to my teacher), The code has been written as simplified as possible to make sure my partner Wegar can understand the code completely so he can do the presentation, I'll keep updating the project if I have time, or rewrite / change the whole project.

## TODO
1. api auth system with pastebin or my own domain
2. better UI design `(i failed art)`

## How does it work?
First of all, when you open the program, you have to get the corrent username and password to pass the authentication`(I made it as simple as possible for my partner)`, I was about to try using [libcurl](https://curl.se/libcurl/c/example.html) with a pastebin that has user data in it, but as far as I know my teacher doesn't like my idea so I have nothing to do but change the whole system with simple strcmp function.

`(Better explanations are commented in the code.)`

## Dependencies
- [imgui](https://github.com/ocornut/imgui) - gui
