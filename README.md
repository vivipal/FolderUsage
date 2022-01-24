### Dependencies

You need to have python3, numpy and matplotlib installed

```console
sudo apt install python3 python3-numpy python3-matplotlib
```

### How to use it

After installing the dependencies clone the code and make it executable:

```console
git clone https://github.com/vivipal/FolderUsage
cd FolderUsage
chmod +x fu
```

Move it /usr/local/bin :

```console
mv fu /usr/local/bin
```

You are now ready to use it as following :

```console
# run in the current working directory
fu

# or provide the path of the folder you want to inspect
fu ~/Documents/
