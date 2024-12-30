# Calculator_project_-Jion![IMG-20241122-WA0003](https://github.com/user-attachments/assets/05770961-9766-4958-afae-e6ac3e15e6c5)

The code starts by importing the `tkinter` (Tk) library, which is the standard GUI library for Python.
  The `Calculator` class is defined, which takes a `master` Tk window as a parameter.
  
  In the `__init__` method, the title of the window is set, and the display entry field is created using `tk.Entry()` and added to the grid layout.

   A list of buttons with their corresponding values is created, and a loop is used to add them to the grid layout. For the "=" button, the `evaluate()` method is called when the button is clicked. For the other buttons, the `add_to_display()` method is called with the button's value as an argument.The `add_to_display()` method adds the given value to the display entry field.
  The `evaluate()` method tries to evaluate the expression in the display entry field using the `eval()` function, and then displays the result in the entry field. If an error occurs, it sets the entry field to "Error".
  Finally, a Tk window instance is created, the `Calculator` class is instantiated, and the main event loop is started using `root.mainloop()`.

This code creates  a functional calculator GUI application that stays open until the user closes the window. The calculator can perform basic arithmetic operations (+, -, *, /) and display the result.
