# gtk3-hello

## build :

```bash
sudo apt install libgtk-3-dev -y
clang `pkg-config --cflags gtk+-3.0` -o hello hello.c `pkg-config --libs gtk+-3.0`
```

## run :
```bash
./hello
```
![Screenshot](/screen.png?raw=true)
