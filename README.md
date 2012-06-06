DRAKON-TEA
==========

TEA cipher in CBC mode with PKCS #7 padding  written in
[DRAKON Editor](http://drakon-editor.sourceforge.net/) + C as a fun exercise.


Files
-----

* tea.drn - original source code in DRAKON Editor format.
* tea.[ch] - generated C code.
* pics/ - generated pictures.


How to try
----------

To compile and run C code:

	make tea && ./tea

To regenerate code, open it in DRAKON Editor and click DRAKON > Generate code.

The generated executable just prints encrypted and decrypted "Hello world!".

Here's the source "code" for `main`:

![main function](https://github.com/dchest/drakon-tea/raw/master/pics/main.png)


License
-------

Public domain (CC-Zero).
Written in 2012 by Dmitry Chestnykh.
