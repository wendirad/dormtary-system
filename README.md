```
                               88888888888        .d888 888       888                                                                        
                                   888           d88P"  888   o   888                                                                        
                                   888           888    888  d8b  888                                                                        
                                   888   8888b.  888888 888 d888b 888  .d88b.  88888b.                                                       
                                   888      "88b 888    888d88888b888 d88""88b 888 "88b                                                      
                                   888  .d888888 888    88888P Y88888 888  888 888  888                                                      
                                   888  888  888 888    8888P   Y8888 Y88..88P 888  888                                                      
                                   888  "Y888888 888    888P     Y888  "Y88P"  888  888                                                      
                                                                                                                                             
                                                                                                                                             
                                                                                                                                             
8888888b.                                 d8b 888                                   .d8888b.                    888                          
888  "Y88b                                Y8P 888                                  d88P  Y88b                   888                          
888    888                                    888                                  Y88b.                        888                          
888    888  .d88b.  888d888 88888b.d88b.  888 888888 .d88b.  888d888 888  888       "Y888b.   888  888 .d8888b  888888 .d88b.  88888b.d88b.  
888    888 d88""88b 888P"   888 "888 "88b 888 888   d88""88b 888P"   888  888          "Y88b. 888  888 88K      888   d8P  Y8b 888 "888 "88b 
888    888 888  888 888     888  888  888 888 888   888  888 888     888  888            "888 888  888 "Y8888b. 888   88888888 888  888  888 
888  .d88P Y88..88P 888     888  888  888 888 Y88b. Y88..88P 888     Y88b 888      Y88b  d88P Y88b 888      X88 Y88b. Y8b.     888  888  888 
8888888P"   "Y88P"  888     888  888  888 888  "Y888 "Y88P"  888      "Y88888       "Y8888P"   "Y88888  88888P'  "Y888 "Y8888  888  888  888 
                                                                          888                      888                                       
                                                                     Y8b d88P                 Y8b d88P                                       
                                                                      "Y88P"                   "Y88P" 
                     __   ___    ____   ____         ___                  __       ___   ___  ___   ____   ___ 
        |    | |__| |__|   |     |   \ |    |   \ / |   | |   |   |    | |__| |\ |  |     |  |   |  |   \ |   |
        |_/\_| |  | |  |   |     |___/ |____|    |  |___| |___|   |_/\_| |  | | \|  |     |  |___|  |___/ |___|
```

A lightweight, console-based dormitory management application written in C++. Designed for educational institutions or small residential facilities to manage student records and room assignments efficiently.

## Features

- Add, view, edit, and delete student records
- Automatic or manual room assignment
- Search students by name or ID
- Export student roster to Rich Text Format (RTF)
- Simple and intuitive menu-driven interface
- ASCII art welcome banner

## Samples
```
  ID   NAME       FATHER NAME   AGE   SEX   YAER DEPART  BLOCK  DORM  BED
------------------------------------------------------------------------- 
17563 Yhonatan      Assefa      19   MALE    2    ECE     374    29    1  
2018  Bethelihem    Tadesse     22   FEMALE  4    CSE     306    3     3  
17563 Yhonatan      Assefa      19   MALE    2    ECE     374    29    1  
17316 Lidet         Fikadu      19   FEMALE  2    CSE     311    72    3  
```

## Requirements

- Windows operating system
- C++ compiler (e.g., g++ via MinGW, or Microsoft Visual Studio)
- Standard C++ libraries only (no external dependencies)

## Build & Run

```bash
git clone https://github.com/wendirad/dormtary-system.git
cd dormtary-system
g++ main.cpp -o dormitory.exe
./dormitory.exe
```

## Usage

Upon launch, the program displays a menu with the following options:

1. Add new student  
2. Display all students  
3. Search student  
4. Edit student information  
5. Delete student  
6. Assign/unassign room  
7. Export list to RTF  
8. Exit  

## Project Structure

- `main.cpp` – Complete source code
- `logo.txt` – ASCII welcome banner
- `Students list.rtf` – Example output file

## License

This project is licensed under the MIT License.
