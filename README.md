# RepoUpdateScript
update your repo the right way


#### On line 15: 
```bash
dpkg-scanpackages debs > Packages
```

#### `debs` is the folder where your packages are stored, change this if needed. Example: Your .deb files are stored in a folder called `alpaca`, so you change it to say: 
```bash
dpkg-scanpackages alpaca > Packages
```
