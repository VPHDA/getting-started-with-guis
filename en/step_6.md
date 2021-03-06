## Text widget

Probably the simplest widget you can add is the **Text** widget, which displays some text on the screen.

- Add `Text` to the import statement (read step 1 of the 'Adding widgets' section if you are not sure how to do this).

- Add a `Text` widget to the GUI (read step 2 of the 'Adding widgets' section if you are not sure where to put this code):

    ```python
    welcome_message = Text(app, text="Welcome to my app")
    ```

    Here we have created a `Text` widget with the name `welcome_message`. The first __argument__ (in the brackets) tells the widget who its boss is! To be more specific, we are telling this `Text` widget that it will be controlled by the `app` object, which we created earlier. The first argument given to any widget always tells it the name of its boss (or 'master').

- Run your code by pressing F5. You should see this text displayed on your GUI.

    ![Text widget](images/app-welcome.png)

- Did you notice that we could tell the `Text` widget what content we wanted it to display by specifying `text="Welcome to my app"`? This is called a keyword argument, because we have specified the keyword `text` and the value we want. We can specify other keyword arguments too, just add them on to the end, separated by commas.

    ```python
    welcome_message = Text(app, text="Welcome to my app", size=40, font="Times New Roman", color="lightblue")
    ```

    Here, we have used keyword arguments for the `size`, `font` and `color` (note the American spelling!).

    ![Text widget](images/app-welcome.png)

    You can specify any font your computer has installed. Colours can be specified as colour names, but not every possible colour has a name, so you can also use hex codes (e.g. #ff0000) to define colours.

