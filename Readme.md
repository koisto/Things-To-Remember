# Things to remember

A page of useful links, tools and code snippets.

##  Using sed to comment out part of a file

```
sed -i '/'"[WORDSTOFIND]"'/ s/^/#/' [FILE]
```

## Using sed to uncomment part of a file

```
sed -i '/'"[WORDSTOFIND]"'/ s/^#*//' [FILE]
```

## Generate a date stamped file in the terminal and write to it

```
$ cat << EOF > "<THE_FILENAME>$(date)<THE_EXT>"
> [The words]
> EOF
```

## Useful tools
crosstool     
buildroot

## Using screen for serial IO

```
$ screen /dev/<console_port> [baud_rate]
```

To exit type `Ctrl+A` followed by `:quit` and `Enter`

## Adafruit USB to TTL Serial Cable

I always forget the pinout.    
* **+5v USB** Red    
* **0v USB** Black     
* **Tx (out)** Green     
* **Rx (in)** White      


