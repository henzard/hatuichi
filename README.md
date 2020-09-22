# hatuichi

A simple tui client for `logmein hamachi`

- minimal
- easy to use
- fast

## Dependencies 

- `bash`
- `logmein-hamachi` 

## Usage 

### installation

1. clone the repo

```bash
git clone https://github.com/yrwq/hatuichi
cd hatuichi
```

2. make hatuichi executable

```bash
chmod +x hatuichi
```

3. copy hatuichi to somewhere in your PATH

```bash
cp hatuichi ~/.local/bin/
```

### starting

1. Start logmein-hamachi daemon

```bash
sudo /etc/init.d/logmein-hamachi start
```

2. Run `hatuichi`


### keys

```sh
1 or k: login
2 or j: logout
3 or r: refresh
4 or p: join a network
5 or n: leave a network
6 or h: go online in a network
7 or l: go offline in a network
8 or c: create a network
0 or q: quit
```

![hatuichi](previews/preview1.png)

## Inspired by

- [dylanaraps](https://github.com/dylanaraps)
    - [torque](https://github.com/dylanaraps/torque)
    - [fff](https://github.com/dylanaraps/fff)

