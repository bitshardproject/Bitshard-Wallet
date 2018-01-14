**1. Clone wallet sources**

```
git clone https://github.com/bitshardproject/Bitshard-Wallet.git
```

**2. Set symbolic link to coin sources at the same level as `src`. For example:**

```
ln -s ../Bitshard bitshard
```

Alternative way is to create git submodule:

```
git submodule add https://github.com/bitshardproject/bitshard.git bitshard
```


**3. Install this dependency:**

```
sudo apt-get install qt5-default
```

**4. Build**

```
mkdir build && cd build && cmake .. && make
```
