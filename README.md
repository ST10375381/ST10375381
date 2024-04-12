# Recipe App

The Recipe App is a console application that allows users to create, display, scale, reset, and delete recipes. It provides a simple interface for managing recipes and their ingredients and steps.

## Features

The Recipe App provides the following features:

1. Create a new recipe by entering ingredients and steps.
2. Display the ingredients and steps of a recipe.
3. Scale the quantities of ingredients in a recipe by a given factor.
4. Reset the quantities of ingredients in a recipe to their original values.
5. Delete a recipe.
6 Exit the application.

## Getting Started

To run the Recipe App, follow these steps:

1. Ensure you have the necessary development environment set up for running C# applications.
2. Copy the provided code into a new C# project in your preferred Integrated Development Environment (IDE).
3. Build the project to compile the code.
4. Run the application.

## Usage

Upon running the Recipe App, you will be presented with a menu of options. To interact with the application, follow these steps:

1. Enter the number corresponding to the desired option and press Enter.
2. Follow the prompts on the screen to perform the chosen action.

### Option 1: Enter a new recipe

This option allows you to create a new recipe by entering the ingredients and steps. Follow the prompts to provide the required information.

### Option 2: Show recipe

This option displays the ingredients and steps of the currently entered recipe, if any. If no recipe has been entered, a message indicating that no recipe is available will be displayed.

### Option 3: Scale recipe

If a recipe has been entered, this option allows you to scale the quantities of ingredients in the recipe by a given factor. Enter the scale factor as prompted.

### Option 4: Reset quantities

If a recipe has been entered, this option allows you to reset the quantities of ingredients in the recipe to their original values. You will be prompted to enter the ingredients and steps for a new recipe.

### Option 5: Delete recipe

This option deletes the currently entered recipe, if any, and sets it to null.

### Option 6: Clear all data and exit

This option exits the application.

## Limitations

The Recipe App has a few limitations:

- It does not provide error handling for invalid user input. Ensure you enter valid input as per the prompts to avoid unexpected behavior.
- The scaling factor is limited to 0.5, 2, or 3. Other values will not be accepted.
- The application does not persist data between runs. Once you exit the application, all entered recipes and data will be lost.

## Conclusion

The Recipe App provides a basic interface for managing recipes. You can create recipes, view their ingredients and steps, scale the recipe quantities, reset quantities, and delete recipes. Feel free to modify and enhance the code as needed to suit your requirements.

Enjoy cooking and experimenting with new recipes!
