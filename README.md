# 2D Graphics Editor (Mini Project)

Hiiiiiiiiii there , I made a 2D Graphics as given as Advaanced C programming Mini project in my college This is a simple command-line program built in C that lets you draw basic geometric shapes like lines, rectangles, triangles, and circles directly inside the terminal window.

---

## Project Details

* **Student Name:** B S Ranjith Kumar
* **Project Name:** 2D Graphics Editor
* **Course:** Advanced C Programming Mini Project
* **Date:** June 2026

---

## Key Features

* **Interactive Menu:** Easy numbers-based menu to choose what you want to draw.
* **Custom Grid Canvas:** Creates an 80x24 screen grid using `_` characters.
* **Shape Drawing:** Uses simple mathematical formulas to light up `*` pixels and form crisp geometric shapes.
* **Aspect Correction:** The circle drawing function automatically adjusts for terminal spacing so your circles look perfectly round, not stretched out.

---

## Menu & Inputs Guide

When running the program, choose a number from the menu and type your coordinates on a single line separated by spaces.

| Menu Option | Shape | What to Type | Example Input |
| :--- | :--- | :--- | :--- |
| **1** | Draw Line | `x1` `y1` `x2` `y2` | `10 5 30 15` |
| **2** | Draw Rectangle | `top-left-x` `top-left-y` `bottom-right-x` `bottom-right-y` | `5 2 25 10` |
| **3** | Draw Circle | `center-x` `center-y` `radius` | `40 12 6` |
| **4** | Draw Triangle | `x1` `y1` `x2` `y2` `x3` `y3` | `10 20 20 5 30 20` |
| **5** | Display Picture | *Just press Enter* | Shows your drawing on screen |
| **0** | Exit | *Just press Enter* | Closes the program safely |