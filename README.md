### DumpProto



For x32 and x64 Windows environments.

Compiles with the latest Windows 10 SDK, C++20, C 17.

No external includes/libs or vcpkg required.



**For x32:**

* `cd <location>/DumpProto`
* `mkdir build \&\& cd build`
* `cmake .. -A Win32`



**For x64:**

* `cd <location>/DumpProto`
* `mkdir build \&\& cd build`
* `cmake ..`



###### **Warning: OUTPUT FILE IN <location>/DumpProto/dump\_proto/<Debug or Release, depending on selected build>**



###### **Warning: Compiles both `item\_proto` and `mob\_proto` if both file pairs are present within the output folder with no option to choose one or the other.**

