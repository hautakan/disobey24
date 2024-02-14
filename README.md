You can use DLL popper to find applications and software that can be used for DLL sideloading. It will display a simple message box if DLL sideloading has been successful.
You need replace the linker rows of the file with what ever is relevant to the software that you are investigating. You can youse PEstudio or SharpDLLProxy for finding functions that your software is expecting to find.

If you want to expand your security research further, you can use the encrypt.py file to encrypt your payloads so that they are not detected by antiVirus softwares:
python3 encrypt.py payload.bin 

Remember to only use these in an environment where you have the permission to do so.
