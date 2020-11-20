# uIHandler

The UIHandler can only create a die currently 
In order to do so you need to import both the Proccesing library and the uIHandler library. 
You then need a object of Button and a Actions object from uIHandler.

Actions
Actions have the constructor (PApplet)
You can then use the ActionsObject.createDie(int high) or ActionsObject.createDie((int)low,(int)high) to create the die action


Button
Button have the constructor ((int) Start x,(int) Width,(int) Start Y,(int) Height,(String) Button Text,PApplet)
You can now assign the button an action in te Proccesing setup function with ButtonObject.addAction(new Action(){public void execute(){ (int)dieResult = ButtonObject.dieAction();  }});
You should now display the button in the Proccesing draw function with ButtonObject.display();
And the finally check if the button is clicked with the ButtonObject.click(); in Proccesings mousePressed(); function



