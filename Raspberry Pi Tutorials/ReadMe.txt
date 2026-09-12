The OLED driver library consists of three files: ssd1306_i2c. c, ssd1306_i2c. h, and oled_fonts. h.
This library is written in C language. Simply copy these three files to the Raspberry Pi, place them in the same directory as the source code files, and compile them together using the gcc compiler.
For example, if the source code for controlling the display of an OLED screen is oled. c, the Raspberry Pi can compile it by running the following command:
gcc -o oled oled.c ssd1306_i2c.c -lwiringPi
Where, the gcc compiler is called, - o represents the generated file, followed by the generated file name, oled. c and ssd1306_i2c. c are source programs, and - lwiringPi is the wiringPi library referencing Raspberry Pie. After compilation, it will become an OLED executable file.
