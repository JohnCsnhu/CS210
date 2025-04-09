📌 Project Summary
This project is a console-based Investment Calculator designed to help users visualize the growth of their investments over time. By inputting the initial investment, monthly deposit, annual interest rate, and investment duration in years, users receive two reports:

Investment Growth Without Monthly Deposits

Investment Growth With Monthly Deposits

The goal of this project was to reinforce object-oriented programming principles in C++, practice class design, and understand compound interest calculations through programmatic logic.

✅ What I Did Well
Object-Oriented Design: I used a well-structured class (Investment) to encapsulate data and behavior related to investments, which helped keep the code clean and modular.

User-Friendly Output: Clear prompts and reports make the program accessible and easy to understand.

Compound Interest Calculations: I successfully implemented the compound interest formula in both scenarios, which gave users an accurate forecast of their investments.

🔧 Opportunities for Improvement
Separation of Concerns: Right now, my Investment class handles both the logic and the output. I could enhance the structure by creating a separate class or module for user interface/output.

Input Validation: Currently, user input is assumed to be valid. Adding input checks would make the program more robust and secure.

Precision and Formatting: Utilizing formatting libraries or built-in C++ utilities for precise currency output would make the reports look more professional.

Performance: While not a big concern for small inputs, caching or optimizing interest calculations could improve efficiency for large-scale simulations.

🧠 Challenges and How I Overcame Them
The most challenging part was getting the compound interest logic exactly right—especially when factoring in monthly deposits and making sure interest was compounded correctly each month. I double-checked my math using online calculators and tested the results manually to ensure accuracy.

To support my learning, I added:

C++ documentation and tutorials to my bookmarks.

Practice projects focusing on class design, control structures, and console I/O.

Stack Overflow threads and GitHub examples for best practices in formatting and calculation logic.

🚀 Transferable Skills
OOP Principles: Designing and structuring a class with constructors, private members, and encapsulated methods is something I can reuse in nearly every C++ project.

Data Modeling: Turning a real-world scenario into a data-driven model is highly relevant to software development, game development, and simulations.

Compound Logic Implementation: Financial logic is applicable in fields like fintech, data science, and analytics.

🧩 Maintainability and Readability
I focused on keeping the code modular, consistent, and well-documented. Here's how:

Used descriptive variable and method names.

Grouped related functionality inside a class (Investment).

Broke down reports into separate methods for clarity.

Kept the main program logic linear and easy to follow.

If I or someone else revisits this code in the future, it will be easy to adapt or extend—for example, adding support for different compounding frequencies or output formats.
