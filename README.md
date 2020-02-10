# CppGames

## Configure DEVC++ w/ SFML
1. You will need TDM-GCC 5.1.0 32-bit compiler (not 64-bit);
2. Configure static linking:
![image](https://user-images.githubusercontent.com/7895269/74130864-c6078200-4beb-11ea-84cd-859496b3fefb.png)
3. Configure library paths:

4. Command line compilation statement: 
```
g++.exe "C:\Users\darba\Desktop\Other Projects\16_Games\14 Chess\main.cpp" -o "C:\Users\darba\Desktop\Other Projects\16_Games\14 Chess\main.exe" -DSFML_STATIC -std=c++11 -I"C:\SFML-2.5.1\include" -I"C:\TDM-GCC-32\include" -I"C:\TDM-GCC-32\lib\gcc\mingw32\5.1.0\include" -I"C:\TDM-GCC-32\lib\gcc\mingw32\5.1.0\include\c++" -I"C:\Windows\System32\" -L"C:\Windows\System32\" -L"C:\SFML-2.5.1\lib" -L"C:\TDM-GCC-32\lib" -L"C:\TDM-GCC-32\mingw32\lib" -lsfml-graphics-s -lsfml-window-s -lsfml-system-s -lopengl32 -lglu32 -lgdi32 -lfreetype -lwinmm
```
