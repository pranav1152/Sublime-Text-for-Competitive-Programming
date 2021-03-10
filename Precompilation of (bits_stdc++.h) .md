# Precompilation of (bits/stdc++.h)
We can speed up compilation time up to 12 times by precompiling all the header files by precompiling the bits/stdc++.h header file. \
For this, first, navigate to the stdc++.h file. This will be located at a directory similar to C:\MinGW\lib\gcc\mingw32\6.3.0\include\c++\mingw32\bits.\
Now right click while pressing Shift to open a Powershell/cmd window there. Run the command g++ -std=c++17 stdc++.h, to compile the header. \
Take care to use the same flags you used in your build system. Check to make sure that the stdc++.h.gch file was created in the directory. \
If cmd window is not opening then go to start then type cmd. Then change directory by typing C:\MinGW\lib\gcc\mingw32\6.3.0\include\c++\mingw32\bits . then execute g++ -std=c++17 stdc++.h make sure stdc++.h.gch is created.
