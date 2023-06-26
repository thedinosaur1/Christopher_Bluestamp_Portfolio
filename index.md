# Lie detector
<!--Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!-->

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Christopher Y.| Lynbrook High | Mechanical Engineering | Incoming Freshman

<img src="Christopher-Headshot.png"  width="225" height="300">


<!--# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Second Milestone
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>-->

# First Milestone - Lie Detector
The Lie Detector is a arduino based project that can tell if you are telling the truth or lying. 

#### What The Parts Do: 
- The arduino is a board that has code from a computer and physical bits that you can connect wires to
- The breadboard connects columns together and connects rows together
- There are resistor four resistors, three of them are 2.2k and one of them is 10k
- Resistors limits the amount of electricity that travels through
- The LED's light up when coded to through a device
- LED lights works by having electricity flow through a microchip which illuminates a light
- The wires just connect everything together

#### How Do The Parts Act Together: 
- The arduino is a board that gives instructions to all the other parts in the system using the code I put into the app
- The wires connect the parts of the arduino to other places like the resistors or the columns
- The resistors limmit the elctricity into the LED lights, so they don't die

#### Technical Progress So Far: 
- I have velcros that I can put my fingers around, when I do, some lights light up
- When I have sweaty fingers, all the lights light up
- When I have not sweaty fingers, only the green LED lights up or sometimes none of the LEDS light up

#### Challenges I Faced: 
- When I was done with my wiring, I tested my LED’s and only my green one turned on
- I tried using different wires, testing my resistors, testing if my other LEDs  were broken, I checked the docs, and I checked if I wired everything correctly
- Turns out my breadboard wasn’t working after I tested if different places on my breadboard connected to eachother
- At last, I realized only half my breadboard 

#### My Plans To Complete My Lie Detector: 
- I plan on adding a heart rate detector
- I'm probally going to solder my wires on soon
- I might add a case to my breadboard 
<!--
<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
-->
# Starter Project - Simon Says
The Simon Says project is a memory game. 
  
#### How To Play: 
  First, you flip the power switch on the board, if you want to, you can also turn on the sound switch. After you press the power switch, the lights will flash in an order, it starts with one flash, then you need to hit that button, then the same button flashes and another button flashes, then you need to hit the buttons in the specific order or else you lose. They game never ends until you hit the wrong button. 
  
#### Materials & What They Do:
- Two batteries powering the simon board
- Inside the four buttons, there are four LED lights
- Behind the LED's, there's a microcontroller which basically registers which buttons I press and if I should continue or restart
- Inside my simon board there is also a resistor which limits the flow of electrical current thats flowing through
- There is also a buzzer that makes a loud noise when I loose
- Lastly there is a decoupling cap which filters out the voltage spikes in my simon board

#### How Do The Components Work Together: 
- When I press buttons, the microcontroller registers them
- The microcontroller of the board gives the LEDs instruction, and give the buzzer instructions
- The batteries give electricity into the decoupling caps
- The decoupling caps remove all the voltage spikes
- The decoupling caps move the electricity into the resistors
- The resistors limmit the electricity and transports it to the microcontroller, the buzzer, and the LEDs

#### Problems I Faced: 
When I finished with everything, one of the lights on my simon board didn't flash, I first tried using a multimeter to see if I put my LED on wrong but I didn’t, Later I found out that the problem was that the solder I put on didn't connect the LED light properly. 

#### Whats Next: 
I am planning on making a lie detector. 

 <iframe width="560" height="315" src="https://www.youtube.com/embed/cEyCkOh2ClY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<!--
# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
-->
