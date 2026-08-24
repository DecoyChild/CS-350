# CS-350

# MorseCode (milestone3)
---
Summarize the project and what problem it was solving.
> This project displays text the corresponding morse code is shown using a red and blue LEDS. <br>
> The red LED represents the dots and the blue LED represents the dashes. <br>
> The button will switch between two messages which are shown in the 16 x 2 LCD <br>

What did you do particularly well?
> Setting the LED dot and dashes using the LED().blink() method to determine the fade timing of the LED. <br>
> Along with the methods to determine the pauses between the LED and messages.

Where could you improve?
> I could have added the option for the user to add a custom message. <br>
> Also could have been more clear in the code comments where the <br>
> message is toggled to better understand how the state machine switches between <br>
> the messages.

What tools and/or resources are you adding to your support network?
> As used daily, the hardware library and datasheets have been an <br>
> invaluable tool to determine methods that are available. <br>
> For the LED finding the blink() method was beneficial to the project. 

What skills from this project will be particularly transferable to other projects and/or course work?
> Working with multiple GPIO devices, ie the LED and buttons along with the 16 x 2 <br>
> display will be invaluable skill going forwards. Learning how to call out specific <br>
> GPIO pins for specific LEDs and other peripherals.

How did you make this project maintainable, readable, and adaptable?
> Using well commented code will allow other programmers down the road understand <br>
> the purpose of each segment. using methods that can be called helps make the program <br>
> able to be used elsewhere. Where some chunks can be broken off, changes and used <br>
> for other projects. 

# Thermostat
---
Summarize the project and what problem it was solving.
> This project imitates a working thermostat. On its initial state, the program will display the current <br>
> temperature, the current state and the set temp. <br>
> When the blue button is pressed the state of the thermostat will cycle <br>
> through its states from off to heat and from heat to cool and from cool to off. <br>
> The red button will increase the set temperature and the blue button will lower the set temperature.

What did you do particularly well?
> Adding new peripherals to the i2c even though it was not part of the required criteria, adding two debugging <br>
> 7-segmented displays worked out rather well. 

Where could you improve?
> More in depth testing would be an area for improvement. There were some simple typos that turned out to <br>
> bypass certain methods. If my testing was more thorough I would have noticed that the LED's didn't cycle <br>
> as quickly as they should have.

What tools and/or resources are you adding to your support network?
> Using online resources like stacked overflow on how to debug certain features <br>
> like issues with UART USB devices. Using similar paths as other programmers <br>
> to help determine what may have caused certain issues is a vital support tool.

What skills from this project will be particularly transferable to other projects and/or course work?
> Learning to use multiple i2c devices and learning how to change peripherals addresses when <br>
> using two otherwise identical devices. A simple solder bridge between two jumpers is all that <br>
> was needed to use serial devices.

How did you make this project maintainable, readable, and adaptable?
> Similar to the other projects, using well documented code helps others coming back <br>
> to understand your intentions. Also when adding new features having well commented code <br>
> makes it easier to fit new modules and methods.
