# XeCrypt
Created by xorloser! Allows common hashing and encryption algorithms used on the Xbox 360 console to be used readily and in the same manner in VC++!

This enables use of the XeCrypt functions as used in the Xbox360 kernel.
This consists of all of the kernel exports from 345 to 402.

Using this header in your Xbox360 source code allows you to import
access to these various functions from the Xbox360 kernel.
This means you can call these functions in your source code
without needing to link any extra libraries.

Using this header in your PC source code allows you to import
access to these various functions from the XeCrypt library.
This means you can call these functions in your source code
by just linking in the XeCrypt library.

Note: "_XBOX" should be defined in order to use these on the Xbox360.
An Xbox360 project created in Visual Studio defines this by default for you.
Leave it undefined to use them on the pc.
