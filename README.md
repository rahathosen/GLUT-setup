# Steps to Setup OpenGL (GLUT) in CodeBlocks(17.12)


Step-1 : Install CodeBlocks Application

Step-2 : Copy the glut.h file and paste it into the directory
		 "C:\ProgramFiles(x86)\CodeBlocks\MinGW\include\GL"

Step-3 : Copy glut32.lib file and paste it into the directory
		 "C:\Program Files(x86)\CodeBlocks\MinGW\lib"

Step-4 : Copy the glut32.dll and paste it into the directory

	"C:\Windows\System32" --(For 32 bit operating system)"
	"C:\WINDOWS\SysWOW64" --(For 64 bit operating system)"


In Every OpenGL Program Include the Following Header Files:-
```c
		#include <windows.h>
		#include <GL/glu.h>
		#include <GL/glut.h>
 ```
    
