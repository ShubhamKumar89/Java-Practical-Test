In the application, above we’ve done the following steps:

Create a new instance of JButton class. In this case, we create a new button and passing the text to display on that button which is “OK” and “Cancel”.
To add an event handler for the button, use the method addActionListener. You see we create an anonymous class as a parameter of the method. We put our code to handle event inside the method actionPerformed. In this case, we show a message dialog to notify that user has clicked the corresponding button.
Then we add buttons to a panel and add this panel to the frame.
