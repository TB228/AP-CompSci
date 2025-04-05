# AP-CompSci

    """
    This script is a recipe generator that allows users to select a style of food 
    (vegetarian, quick, or comfort) and choose a recipe from the available options. 
    Once a recipe is selected, the script provides a link to the recipe.

    Functions:
        display_recipes(style, choices, recipes):
            Displays a list of recipes for the selected style and prompts the user 
            to choose one. If the choice is valid, it provides the recipe link.

    Variables:
        veg (dict): A dictionary containing vegetarian recipe names as keys and 
            their corresponding URLs as values.
        vegChoices (str): A string listing the available vegetarian recipes.

        quick (dict): A dictionary containing quick recipe names as keys and 
            their corresponding URLs as values.
        quickChoices (str): A string listing the available quick recipes.

        comfort (dict): A dictionary containing comfort food recipe names as keys 
            and their corresponding URLs as values.
        comfortChoices (str): A string listing the available comfort food recipes.

        style (str): A variable to store the user's selected style of food.

    Usage:
        Run the script and follow the prompts to select a style of food and a recipe.
        The script will display the recipe link for the selected option.
    """
