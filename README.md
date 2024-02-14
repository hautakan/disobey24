Use Procmon to find software with DLL sideloading possibilities. Set the following filtering rules:

PATH contains <your folder name where the executable(s) are>
RESULT is PATH NOT FOUND
RESULT is NAME NOT FOUND

You can use DLL popper to find applications that can be used for DLL sideloading. It will display a simple message box if DLL sideloading has been successful.
You need replace the linker rows of the file with what ever is relevant to the software that you are investigating. You can use for example PEstudio or SharpDLLProxy to look into the original .dll file for functions that your software is expecting to find.

Remember to only use these in an environment where you have the permission to do so.
