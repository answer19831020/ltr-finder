# Installation #
1. check out the latest codes:
```
svn checkout http://ltr-finder.googlecode.com/svn/trunk/ ltr-finder
```
2. make the executable file:
```
cd ltr-finder
make
```
3. then add the current path to $PATH:
```
echo "export PATH=\$PATH:/path/to/ltr-finder" >> ~/.bashrc
```

NOTE: change **/path/to/ltr-finder** to the real path.

NOTE: there is a **`\`** in front of **`$PATH`**