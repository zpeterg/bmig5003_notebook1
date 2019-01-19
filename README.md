# bmig5003_notebook1
Project for BMIG5003 - notebook that does text-parsing to anticipate words based on proximity to each other.

# Features
This is a python Jupyter notebook that:
1. Loads a .txt file.
2. Cleans it (removes most punctuation).
3. Breaks it into an array.
4. Cuts the array down to only include segments bounded by "start" and "stop" words (and ended completely with a "finish" word).
5. Finds words within a certain proximity and loads them into a SQLite database based on relative position.
6. Finds the words within a specific proximity to a specified word, and gives count and percentage of each.

# Install
1. Clone ```git clone https://github.com/zpeterg/bmig5003_notebook1.git```
2. Create environment: ```conda env create -f environment.yml```
3. Activate environment: ```conda activate peter_env```
4. Open the Jupyter notebook: ```jupyter notebook peter_notebook.ipynb```

# Run
1. In the Jupyter notebook, click Cell -> Run All
Optional:
2. Update the global variables if desired and run again.
3. Add a new .txt file and redirect to it in the global variables.
