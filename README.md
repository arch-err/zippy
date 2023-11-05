# zippy
Zippy & Unzippy are two small tools used in creating a part of a CTF-challenge.

# Origin & Challenge

Zippy and Unzippy are tools created for creating a problem for a CTF-challenge, and then solving the problem. The challenge in mind was to give the user a zip file that's password protected with the filename. In this file, there is another zip file that follows the same rule. This should be repeated for a few thousand layers in depth, making sure it was impossible to do it by hand. The purpose of the challenge is to have to learn some bash-scripting. If you want to **try the challenge for yourself, download zippy and follow the usage instructions below. Then come up with a sollution to reverse the whole thing.**

# Usage

## zippy

The following command will, layer by layer, zip up a file for *n* amount of times.
```
./zippy <file> <depth>
```


## unzippy

The following command will unzip up a file, go into that folder, and unzip that file over and over until there are no more zipfiles.

```
./unzippy <file> 
```

# Future

These scripts don't have much of a use, other than having a bit of fun. I hope to be able to turn this script into somewhat of a useful tool, but as of now, zippy and unzippy are just two mostly useless scripts.
