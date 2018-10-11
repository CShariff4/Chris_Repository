# c12 Objects & Reading Python
----
1. Clone this repository locally
2. Create a branch
3. Create your own program file: ```touch graphicsSandbox.py```
4. Commit:

```
git add <the file you just made>
git commit -m "Creates <filename>"
```

5. Link to remote repository and push

```
git remote add <label> <url>
git push -u <label> master
```

6. Look through the code of ```graphics.py``` (included in this repository)

7. Complete the following steps. For each step, test by running ```python3 <filename>```, edit if necessary, then commit once it works. Get help from your team members if you get stuck along the way. You can look at each other's code through the shared repository. Please don't copy paste: study it to understand it then hide the browser and try to do it on your own.

   * import the graphics library
   
   ```
   from graphics import *
   ```
   
   * create an file drawing.py
   * create a window:
   
   ```
   win = GraphWin("Graphics Sandbox", 401, 401)
   ```
   
   * set the coordinate system for the window (so that the center of the window is the 0,0)
   
   ```
   win.setCoords(-200, -200, 200, 200)
   ```
   
   * Make a point
   * Make a circle
   
8. Push to github: ```git push```. Do this at the end of class, regardless of how far you get in the activity.
