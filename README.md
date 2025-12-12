# Hotel Management System - Refactoring Project
This repository contains the refactored version of a legacy Hotel Management System application. This project is part of the COMP6106001 - Code Reengineering course assignment (AOL).

# Our Group :
1. 2702369516 - MUHAMMAD ASLAM SIDDIQ
2. 2702376635 - PUTU JEYAN WAHYUDA
3. 2702379012 - MIKHAEL VICTOR SIAGIAN

# 📂 Original Source (Legacy Code)
The original code was retrieved from an open-source repository containing several "Code Smells" used as a case study for this refactoring project.

- Original Repository: [Hotel-Management-CLI by AnishDaru](https://github.com/AnishDharu/Hotel-Management-CLI)
- Target File (Smelly Code): [Main.java (Permalink)](https://github.com/AnishDharu/Hotel-Management-CLI/blob/4e91a89e9f0c6f3ac76b965f919e8314d68f98fd/Main.java)

# 🛠️ Refactoring Changes
The original code consisted of a single God Class (Main.java) with over 300 lines of code, mixed responsibilities, and duplicated logic.

Key Improvements:

1. Modularization: Split the single Main.java file into separate classes (Hotel.java, HotelData.java, Food.java, SingleRoom.java, DoubleRoom.java, DataSaver.java) to adhere to the Single Responsibility Principle.
2. Naming Conventions: Renamed variables and classes to follow Java standards (e.g., Doubleroom → DoubleRoom, hotel_ob → hotelData).
3. Extract Method: Refactored the bill() method to remove severe code duplication (reducing repetitive switch-case logic).
4. Error Handling: Fixed class hierarchy issues caused by legacy serialization.
