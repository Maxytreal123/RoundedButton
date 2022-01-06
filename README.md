# Rounded Buttons

A Minecraft Based Rounded Buttons

Note You need GuiUtils by Anshg_#4787 to Use this RoundedButton Module

# How to use

- Creating a Rounded buttons (There is 3 different RoundedButton Constructors)

```java
// Use this in the initGui in your GuiClass
// This is just an example

// First Constructor Example
this.buttonList.add(new RoundedButton(9, width, height, 3, "text")); // Change [9, width, height, 3, "text"] to [YOUR_ID, X, Y, RADIUS, TEXT]

// Second Constructor Example
this.buttonList.add(new RoundedButton(9, width, height, 32, 32, 3, "text")); // Change [9, width, height, 32, 32, 3, "text"] to [YOUR_ID, X, Y, SIZE_X, SIZE_Y, RADIUS, TEXT]

// Third Constructor Example
/*
* Default Radius for this Constructor is 3
*/
this.buttonList.add(new RoundedButton(9, wdith, height, "text")); // Change [9, width, height, "text"] to [YOUR_ID, X, Y, TEXT]

/*
* Colors are set to 0x44000000 Which is Transparent Gray You can Change that in the Draw Button in RoundedButton.java
*/
```

Big Thanks to Whomaxiswell#7002 for making this <3!
