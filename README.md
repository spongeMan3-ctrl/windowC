# windowC
## Simple, working window app written in C.

This is my **easy-to-use** starter code for making GTK windows in C. It's clean, functional, and a great place to begin!

---

### More info

`pkg-config` `sudo apt install libgtk-3-dev pkg-config`

#### Compile


```bash
gcc main.c -o main $(pkg-config --cflags --libs gtk+-3.0)
