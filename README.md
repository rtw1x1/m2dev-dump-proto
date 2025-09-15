### DumpProto



For x32 and x64 Windows environments.

Uses LZO 2.10.

Compatible with latest Windows 10 SDK Platform, C++ 20, C 17.



No need for external includes/lib folder or vcpkg!



**For x32:**

* `cd <location>/DumpProto`
* `mkdir build \&\& cd build`
* `cmake .. -A Win32`



**For x64:**

* `cd <location>/DumpProto`
* `mkdir build \&\& cd build`
* `cmake ..`



###### **Warning: Builds both `item\_proto` and `mob\_proto` if both file pairs are present in output directory (no option to select one of them)**



###### **Warning: EXE output in `<location>/DumpProto/dump\_proto/<x64 (if built for x64)>/<Debug or Release, depending on build target>`**

