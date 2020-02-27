# Things to remember

A page of useful links, tools and code snippets.

##  Using sed to out part of a file

```
sed -i '/'"[WORDSTOFIND]"'/ s/^/#/' [FILE]
```

## Using sed to uncomment part of a file

```
sed -i '/'"[WORDSTOFIND]"'/ s/^#*//' [FILE]
```

## Generate a date stamped file in ther terminal and write to it

```
$ cat << EOF > "<THE_FILENAME>$(date)<THE_EXT>"
> [The words]
> EOF
```

## Useful tools
crosstool
buildroot

# Using screen for serial IO

```
$ screen /dev/<console_port> [baud_rate]
```
