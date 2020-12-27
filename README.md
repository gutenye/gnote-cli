Install
--------

```
edit ~/.gnoterc
  dir: ~/note
  output: ~/tags
  mark: ∗

# macOS
brew install gutenye/alt-gnote
brew start  gnote
tail -f /usr/local/var/log/gnote.log

# Linux
pacman -S gnote

# From source
go get -u github.com/gutenye/gnote
```

Development
--------

```
$ dep ensure
$ ./ake build
```
