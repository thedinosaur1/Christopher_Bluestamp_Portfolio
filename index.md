# Lie detector
Have you ever wanted to find out if your sibiling(s) are lying about eating all the snacks in the house? Then wonder no further! With this new technology, you can find out if the cookie monster or your sibiling(s) ate all the snacks in the house! By measuring galvanic skin response and heart rate, we can find out if someone is lying to you. (most of the time)

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Christopher Y.| Lynbrook High | Mechanical Engineering | Incoming Freshman

<img src="Christopher-Headshot.png"  width="225" height="300">


<!--# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
#### What I've Accomplished Since My Previous Milestone
I added a algorithm to find my average heart beat and galvanic skin response. I also added a 3d printed box to hold lie detector in. 

#### My Biggest Challenges I've Faced
One of my biggest challenges I faced was when I finnished with my lie detector, half my breadboard didn't work, but my arduino was on the half that did work, so I didn't know half my breadboard didn't work. When I tested it, only one of my LEDs turned on. I tested my LED, my resistor, my wires, my arduino, and I finally testd my breadboard. And I eventually found out and got a new breadboard. 

#### My Biggest Triumphs At BSE
I feel like my biggest triumph at BSE was coding my algorithm. When I first started making my algorithm, I had no idea what to do and how to find my average heart rate and average galvanic skin response. I eventually asked for help and got two codes, one for my algorithm and one for my default code. From then on, I combined both of the codes together and I had my final code. I still had to spend some days changing some things because some things didn't work but I finnished it in the end. 

#### key topics you learned about
I learned a lot about engineering. I learned how to code with arduino, I learned how to do the basics of 3d printing, I learned the basics of Ohm's law, and I learned how to solder. 

- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
-->
# Second Milestone - Heartbeat Sensor
The heartbeat sensor can detect your heartbeat.  

#### What I’ve accomplished So Far And How It Works Toward My Final Goal
I completed my heart rate sensor and my OLED screen which displays my heart rate. My final goal is to have an algorithm that changes depending on the person's sweat and their heartbeat to detect if they’re lying.

#### Challenges I’ve Faced 
I faced two main challenges, which are needing to combine two codes together and my delays for my LEDs causing my heartbeat monitor and galvanic skin response to measure slower. I solved my first problem, combining two codes together, by making a state machine which is basically a plan that states what should go in what order for my lie detector and heartbeat sensor. After that, I slowly implemented my state machine into my code by slowly combining both codes together and it turned out working. For my second problem, I needed my delays to run without delaying my arduino because my delays stop my entire arduino for a bit and that will cause my heart rate and lie detector to pause for a bit which would slow it down, so I researched it and found out the millis command which is basically the delay command without pausing, however I couldn’t get the command to work, so I just made it so that when one LED would turn on, it would turn off all the other LEDs.

#### What Needs To Be Completed Before Your Final Milestone 
I need want to make a box around my lie detector so it looks more professional and I would also like to add a basic algorithm that changes depending on if the person im testing sweats a lot, has high resting heart beat or gets nervous easily.

<iframe width="560" height="315" src="https://www.youtube.com/embed/hQsp0eu9h-I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# First Milestone - Lie Detector
The Lie Detector is an arduino based project that can tell if you are telling the truth or lying. 

#### What The Parts Do: 
The arduino is a board that has code from a computer and physical bits that you can connect wires to. The breadboard connects columns together and connects rows together. There are four resistors, three of them are 2.2k and one of them is 10k, resistors limit the amount of electricity that travels through. The LED's light up when coded to through a device, LED lights work by having electricity flow through a microchip which illuminates a light. The wires just connect everything together. 

#### How Do The Parts Act Together: 
The arduino is a board that gives instructions to all the other parts in the system using the code I put into the app. The wires connect the parts of the arduino to other places like the resistors or the columns. The resistors limit the electricity into the LED lights, so they don't die. And the breadboard connects the rows and columns together. 

#### Technical Progress So Far: 
I have velcros that I can put my fingers around, when I do, some lights light up. When I have sweaty fingers, all the lights light up. When I don’t have sweaty fingers, only the green LED lights up or sometimes none of the LEDS light up

#### Challenges I Faced: 
When I was done with my wiring, I tested my LED’s and only my green one turned on. I tried using different wires, testing my resistors, testing if my other LEDs  were broken, I checked the docs, and I checked if I wired everything correctly. Turns out my breadboard wasn’t working after I tested if different places on my breadboard connected to each other. At last, I realized only half my breadboard. So I got a new breadboard that worked. 

#### My Plans To Complete My Lie Detector: 
I plan on adding a heart rate detector, I'm probably going to solder my wires on soon. I might add a case to my breadboard. Also I might add an algorithm that changes depending on different peoples galvanic skin response and heart rate. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/StfrcpoQP14" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Starter Project - Simon Says
The Simon Says project is a memory game. 
  
#### Materials & What They Do:
There are two batteries powering the simon board, inside the four buttons, there are four LED lights that light up when told to through code. Behind the LED's, there's a microcontroller which basically registers which buttons I press and if I should continue or restart. Inside my simon board there is also a resistor which limits the flow of electrical current that's flowing through, there is also a buzzer that makes a loud noise when I loose. Lastly there is a decoupling cap which filters out the voltage spikes in my simon board. 

#### How Do The Components Work Together: 
When I press buttons, the microcontroller registers them, giving the LEDs instructions, and gives the buzzer instructions, for example if I lost, then the buzzer will buzz and the LEDs will stop lighting up. The batteries give electricity into the decoupling caps, the decoupling caps remove all the voltage spikes that are getting put through the system, then the decoupling caps move the electricity into the resistors. The resistors limit the electricity and transports it to the microcontroller, the buzzer, and the LEDs. 

#### Problems I Faced: 
When I finished everything, one of the lights on my simon board didn't flash. I first tried using a multimeter to see if I put my LED on wrong but I didn’t. Later I found out that the problem was that the solder I put on didn't connect the LED light properly. 

#### Whats Next: 
I am planning on making a lie detector. 

 <iframe width="560" height="315" src="https://www.youtube.com/embed/cEyCkOh2ClY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


# Schematics 
This is my schematic to my box for my lie detector. 
Link: https://cad.onshape.com/documents/3ba0a5e8628ea6f2311e0273/w/f3892129fdbb3340f6cfe332/e/1157ac02c916d4a12a24daf8

# Code

```c++
/*
   Sketch to handle each sample read from a PulseSensor.
   Typically used when you don't want to use interrupts
   to read PulseSensor voltages.

   Here is a link to the tutorial that discusses this code
   https://pulsesensor.com/pages/getting-advanced

   Copyright World Famous Electronics LLC - see LICENSE
   Contributors:
     Joel Murphy, https://pulsesensor.com
     Yury Gitman, https://pulsesensor.com
     Bradford Needham, @bneedhamia, https://bluepapertech.com

   Licensed under the MIT License, a copy of which
   should have been included with this software.

   This software is not intended for medical use.
*/

/*
   Every Sketch that uses the PulseSensor Playground must
   define USE_ARDUINO_INTERRUPTS before including PulseSensorPlayground.h.
   Here, #define USE_ARDUINO_INTERRUPTS false tells the library to
   not use interrupts to read data from the PulseSensor.

   If you want to use interrupts, simply change the line below
   to read:
     #define USE_ARDUINO_INTERRUPTS true

   Set US_PS_INTERRUPTS to false if either
   1) Your Arduino platform's interrupts aren't yet supported
   by PulseSensor Playground, or
   2) You don't wish to use interrupts because of the side effects.

   NOTE: if US_PS_INTERRUPTS is false, your Sketch must
   call pulse.sawNewSample() at least once every 2 milliseconds
   to accurately read the PulseSensor signal.
*/
#define USE_ARDUINO_INTERRUPTS false
#include <PulseSensorPlayground.h>
#include <SPI.h>
#include <Wire.h>
#include <Adafruit_GFX.h>
#include <Adafruit_SSD1306.h>

Adafruit_SSD1306 srituhobby = Adafruit_SSD1306(128, 64, &Wire);

#define sensor A1
#define Highpulse 35
/*
   The format of our output.

   Set this to PROCESSING_VISUALIZER if you're going to run
    the Processing Visualizer Sketch.
    See https://github.com/WorldFamousElectronics/PulseSensor_Amped_Processing_Visualizer

   Set this to SERIAL_PLOTTER if you're going to run
    the Arduino IDE's Serial Plotter.
*/
const int OUTPUT_TYPE = SERIAL_PLOTTER;

/*
   Pinout:
     PULSE_INPUT = Analog Input. Connected to the pulse sensor
      purple (signal) wire.
     PULSE_BLINK = digital Output. Connected to an LED (and 1K series resistor)
      that will flash on each detected pulse.
     PULSE_FADE = digital Output. PWM pin onnected to an LED (and 1K series resistor)
      that will smoothly fade with each pulse.
      NOTE: PULSE_FADE must be a pin that supports PWM. Do not use
      pin 9 or 10, because those pins' PWM interferes with the sample timer.
     THRESHOLD should be set higher than the PulseSensor signal idles
      at when there is nothing touching it. The expected idle value
      should be 512, which is 1/2 of the ADC range. To check the idle value
      open a serial monitor and make note of the PulseSensor signal values
      with nothing touching the sensor. THRESHOLD should be a value higher
      than the range of idle noise by 25 to 50 or so. When the library
      is finding heartbeats, the value is adjusted based on the pulse signal
      waveform. THRESHOLD sets the default when there is no pulse present.
      Adjust as neccesary.
*/

int sX = 0;
int sY = 60;
int x = 0;
int Svalue;
int value;
long Stime = 0;
long Ltime = 0;
int count = 0;
int Bpm = 0;
int redLED = 4;
int blueLED = 3;
int greenLED = 2;
const int PULSE_INPUT = A1;
const int PULSE_BLINK = LED_BUILTIN;
const int PULSE_FADE = 5;
const int THRESHOLD = 300;   // Adjust this number to avoid noise when idle

int counter = 0;
int counter2 = 1;
int counter3 = 0;
unsigned int allbpm = 0;
unsigned int allgsr = 0;
int averageBPM = 0;
int averageGSR = 0;
int myBPM1;
int myBPM;
/*
   samplesUntilReport = the number of samples remaining to read
   until we want to report a sample over the serial connection.

   We want to report a sample value over the serial port
   only once every 20 milliseconds (10 samples) to avoid
   doing Serial output faster than the Arduino can send.
*/
byte samplesUntilReport;
const byte SAMPLES_PER_SERIAL_SAMPLE = 5;

/*
   All the PulseSensor Playground functions.
*/
PulseSensorPlayground pulseSensor;

void setup() {
  /*
     Use 115200 baud because that's what the Processing Sketch expects to read,
     and because that speed provides about 11 bytes per millisecond.

     If we used a slower baud rate, we'd likely write bytes faster than
     they can be transmitted, which would mess up the timing
     of readSensor() calls, which would make the pulse measurement
     not work properly.
  */
  Serial.begin(9600);
  //initializes my lcd 
  srituhobby.begin(SSD1306_SWITCHCAPVCC, 0x3C);// Address 0x3C for 128x32
  delay(1000);
  srituhobby.clearDisplay();//removes everything on the lcd

  //initializing LED pins
  pinMode(greenLED, OUTPUT);
  pinMode(blueLED, OUTPUT);
  pinMode(redLED, OUTPUT);
  digitalWrite(greenLED, HIGH);
  delay(500);
  digitalWrite(greenLED, LOW);
  digitalWrite(blueLED, HIGH);
  delay(500);
  digitalWrite(blueLED, LOW);
  digitalWrite(redLED, HIGH);
  delay(500);
  digitalWrite(redLED, LOW);
  // Configure the PulseSensor manager.
  pulseSensor.analogInput(PULSE_INPUT);
  pulseSensor.blinkOnPulse(PULSE_BLINK);
  pulseSensor.fadeOnPulse(PULSE_FADE);

  pulseSensor.setSerial(Serial);
  pulseSensor.setOutputType(OUTPUT_TYPE);
  pulseSensor.setThreshold(THRESHOLD);

  // Skip the first SAMPLES_PER_SERIAL_SAMPLE in the loop().
  samplesUntilReport = SAMPLES_PER_SERIAL_SAMPLE;
  counter = 0;

  // Now that everything is ready, start reading the PulseSensor signal.
  if (!pulseSensor.begin()) {
    /*
       PulseSensor initialization failed,
       likely because our Arduino platform interrupts
       aren't supported yet.

       If your Sketch hangs here, try changing USE_PS_INTERRUPT to false.
    */
    for(;;) {
      // Flash the led to show things didn't work.
      digitalWrite(PULSE_BLINK, LOW);
      delay(50); Serial.println('!');
      digitalWrite(PULSE_BLINK, HIGH);
      delay(50);
    }
  }
}

void loop() {
  srituhobby.setTextColor(SSD1306_WHITE);
  delay(10); 
  counter3++;
  Svalue = analogRead(sensor);
  value = map(Svalue, 0, 1024, 0, 45);

  if (counter3 >= 3) {
  BPM();
  counter3 = 0;
  }
  int y = 60 - value;

  if (x > 128) {
    x = 0;
    sX = 0;
    srituhobby.clearDisplay();
  }
  srituhobby.drawLine(sX, sY, x, y, WHITE);
  sX = x;
  sY = y;
  x ++;
    if (counter == 0) {
        int gsrPL = analogRead(A0);
        if (myBPM > 0 && gsrPL > 0) {
        Serial.print("BPM: ");                        // Print phrase "BPM: " 
        Serial.println(myBPM); 
        allbpm = myBPM + allbpm;

        counter2++;
        Serial.println(counter2);

        Serial.print("GSR: ");
        Serial.println(gsrPL);
        allgsr = gsrPL + allgsr;
    }
    averageBPM = allbpm/counter2;
    averageGSR = allgsr/counter2;
    Serial.print("ALL GSR: ");
    Serial.println(allgsr);
  Serial.print("average BPM so far: ");
  Serial.println(averageBPM);
  Serial.print("Average GSR so far: ");
  Serial.println(averageGSR);

  srituhobby.setCursor(0, 0);
  srituhobby.setTextSize(2);
  srituhobby.setTextColor(SSD1306_WHITE);
  srituhobby.println("Calibrate");
  srituhobby.display();

    }

  else if (counter == 1) {
    Serial.print("AVERAGE BPM: ");
    Serial.println(averageBPM);
    Serial.print("AVERAGE GSR: ");
    Serial.println(averageGSR);
    srituhobby.clearDisplay();
      counter = 2;
  }
  if (counter2 > 51 && counter == 0) {
    counter = 1;
  }

        if (counter == 2) {
        int gsrPL = analogRead(A0);
        Serial.print("GSR: ");
        Serial.println(gsrPL);
        Serial.print("BPM: ");
        Serial.println(myBPM);
        if (gsrPL > averageGSR + 50 && myBPM > averageBPM + 15) 
        {
          digitalWrite(greenLED, LOW);
          digitalWrite(blueLED, LOW);
          digitalWrite(redLED, HIGH);
        }
        else if (gsrPL > averageGSR && myBPM > averageBPM)
        {
          digitalWrite(redLED, LOW);
          digitalWrite(greenLED, LOW);
          digitalWrite(blueLED, HIGH);
        }
        else if (gsrPL < averageGSR - 20 && myBPM < averageBPM - 5)
        {
          digitalWrite(blueLED, LOW);
          digitalWrite(redLED, LOW);
          digitalWrite(greenLED, HIGH);
        }



  srituhobby.setCursor(60, 0);
  srituhobby.setTextSize(2);
  srituhobby.setTextColor(SSD1306_WHITE);
  srituhobby.print(myBPM);
  srituhobby.print("   ");

  srituhobby.setCursor(0, 0);
  srituhobby.print("BPM :");
  srituhobby.display();


      }
}

void BPM() {
  Stime = millis() - Ltime;
  if (value > Highpulse) {
    count++;
  }
    if (Stime / 1000 >= 6) {
      myBPM = count * 10;
      Ltime = millis();
      count = 0;
    }
}
```
<!--
# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Heartbeat Sensor | Finding your heart beat | $24.99 | <a href="https://pulsesensor.com/products/pulse-sensor-amped"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
-->




