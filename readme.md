# Assembly README

To build the assembly project, follow these steps:

1. Open a terminal or command prompt.
2. Navigate to the project directory (src\hello_world).
3. Run the following command:

```
..\..\dependency\nasm\nasm.exe -f win64 '..\..\src\hello world\hello_world.asm' -o ..\..\obj\hello_world.obj
..\..\dependency\golink\GoLink.exe ..\..\obj\hello_world.obj /entry main /console kernel32.dll
```

Replace `hello_world.asm` with the name of your assembly file.

4. If the build is successful, an executable file named `hello_world.exe` will be generated in the same directory.