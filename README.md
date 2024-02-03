You can DLL popper to find applications and software that are vulnerable to DLL sideloading. It will display a simple message box if DLL sideloading has been successful.
You need replace the linker rows of the file with what ever is relevant to the software that you are investigating. You can youse PEstudio or SharpDLLProxy for finding functions that your software is expecting to find.

Use the encrypt.py file to encrypt your payloads so that they are not detected by AntiVirus softwares:
python3 encrypt.py payload.bin 

