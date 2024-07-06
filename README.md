# Cookie Cook Book

Cookie Cook Book is a small practise project taken from a tutorial from Ultimate C# Masterclass for 2024
course on Udemy, learning about using interfaces, SRP, Dependency-Injection/Dependency-Inversion, abstract methods, overrides and namespacing etc.

## Usage
Below is an example of what the program displays on console window when you run the application on Visual Studio. The Existing recipes shown is what is saved locally in either recipes.json or recipes.txt (depending on what format you decide to save it as). 

Note that recipes.json/recipes.txt can be found bin/Debug/net7.0.

```Existing recipes are:

*****1*****
Wheat flour. Sieve. Add to other ingredients.
Spelt flour. Sieve. Add to other ingredients.
Sugar. Add to other ingredients.

Create a new cookie recipe! Available ingredients are:
1. Wheat flour
2. Spelt flour
3. Butter
4. Chocolate
5. Sugar
6. Cardamon
7. Cinnamon
8. Cocoa powder
Add an ingredient by its ID, or type anything else if finished.
```

Whilst running the application, you select recipes by typing in Id shown in the list i.e 1, 2, 3. Once finished, hit enter and it will complete the program and display the ingredients you have selected. The application will end by this point. If you run the application again, it will display the list of ingredients you selected appended to the existing previous ingredients.

note this program is set to save the ingredients as .json format. To change to .txt format, go to program.cs file on line 7 you will see the following,

```
const FileFormat Format = FileFormat.Json;
```
Change FileFormat.Json to FileFormat.Txt.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

