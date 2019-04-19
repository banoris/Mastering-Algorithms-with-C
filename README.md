# Build step example for Linux

```
# Install makedepend
sudo apt install xutils-dev

# Run code for Chapter 10: Heaps and Priority Queue
$ cd examples_unix/examples/heap
$ make ALGOWC_TOPDIR=../../ -f heap.mak all

# Run the executables
$ ./ex-1.exe 
Inserting 005
Heap size is 1
Node=005
Inserting 010
Heap size is 2
Node=010
Node=005
Inserting 020
Heap size is 3
Node=020
Node=005
Node=010
...
```




## Example files for the title:
	  
# Mastering Algorithms with C, by Kyle Loudon
	  
[![Mastering Algorithms with C, by Kyle Loudon](http://akamaicovers.oreilly.com/images/9781565924536/cat.gif)](https://www.safaribooksonline.com/library/view/title/1565924533//)
	  
The following applies to example files from material published by O’Reilly Media, Inc. Content from other publishers may include different rules of usage. Please refer to any additional usage rights explained in the actual example files or refer to the publisher’s website.
	  
O'Reilly books are here to help you get your job done. In general, you may use the code in O'Reilly books in your programs and documentation. You do not need to contact us for permission unless you're reproducing a significant portion of the code. For example, writing a program that uses several chunks of code from our books does not require permission. Answering a question by citing our books and quoting example code does not require permission. On the other hand, selling or distributing a CD-ROM of examples from O'Reilly books does require permission. Incorporating a significant amount of example code from our books into your product's documentation does require permission.
	  
We appreciate, but do not require, attribution. An attribution usually includes the title, author, publisher, and ISBN.
	  
If you think your use of code examples falls outside fair use or the permission given here, feel free to contact us at <permissions@oreilly.com>.
	  
Please note that the examples are not production code and have not been carefully testing. They are provided "as-is" and come with no warranty of any kind.
