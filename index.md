# IoT Pollution Monitor
Is it safe outside? The IoT Pollution Monitor uses FeatherWing boards with arduino IDE to keep track of the temperature and air quality outside. The data is sent to an Adafruit browser where pollution data can be accessed from anywhere in the world online! This project can track harmful radiation during natural disasters and prevent people from going into dangerous areas. This Pollution Monitor can make the environment around where it is placed safer and inform users from potential threats that need to be dealt with.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Rishaan D | Fremont High School | Electrical Engineering | Incoming Freshman |

<img src="RishaanD.jpg" width="400" height="500">

```HTML
# Modifications 

**Don't forget to replace the text below with the embedding for your modifications video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- what are the modifications?
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE
  


# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

# First Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

I chose this project to learn about IoT, or known as the Internet of Things. I want to learn how to use hardware in a different approach. How to send data back to the computer and view it online. Additonally, this project will be very helpful in keeping the environment inside and outside my house safe from air pollution.

There are 5 parts to the IoT Monitor's assembly. The FeatherWing Doubler makes it possible for Feather boards and sensors to connect into one build. The Feather M4 express is the microcontroller which takes on the coding tasks and performs them physically. The AirLift FeatherWing enables wifi and co-proccessing for the Feather M4 express. This makes it possible for the Feather M4 express to connect to the computer and recieve code as well as send data back to the computer. 

The temperature/humidity sensor and the air quality sensor are wired to the FeatherWing Doubler to connect to the Feather M4 express. This enables the microcontroller to connect and control the sensors. The data collected from these sensors is sent back to the computer to display the data online.

Some challenges I faced were seperating the four connected wires. The wires were hard to pull apart without ripping some of the protective plastic layer. I solved this by using a tweser to pull apart the wires and then cutting portions of the wire that had been ripped. Another challenge was understanding how the seperate modules needed to be soldered before connecting all of the modules together. I solved this by researching the pieces, such as the FeatherWing dobuler and the different pins it uses. 

- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones: Putting breadboards together with no previous knowledge/instruction. (used research to solve).
- What your plan is to complete your project
```
# Schematics 
<img src="Schematics.png" width="500" height="300">

[Schematics link](https://learn.adafruit.com/diy-air-quality-monitor/wiring)  

```HTML

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

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Adafruit Feather M4 Express featuring ATSAMD51 | Stores code and processing files | $22.95 | <a href="https://www.adafruit.com/product/3857"> Link </a> |
| Adafruit AirLift FeatherWing | Uses ESP32 to connect to WiFi and transfer data | $12.95 | <a href="https://www.adafruit.com/product/4264"> Link </a> |
| PM2.5 Air Quality Sensor and breadboard adapter kit | Monitors air quality using lasers and dust concentrations | $39.95 | <a href="https://www.adafruit.com/product/3686"> Link </a> |
| Adafruit BME280 12C or SPI | Temperature Humidity Pressure Sensor | $14.95 | <a href="https://www.adafruit.com/product/2652"> Link </a> |
| FeatherWing Doubler | Feather Board prototyping add-on | $7.50 | <a href="https://www.adafruit.com/product/2890"> Link </a> |
| Flanged Weatherproof Enclosure with PG-7 Cable Glands | An enclosure to protect projects from weather | $9.95 | <a href="https://www.adafruit.com/product/3931"> Link </a> |
| Silicone Stranded Cable | 4 connected 30 AWG wires | $1.95 | <a href="https://www.adafruit.com/product/3889"> Link </a> |

```HTML
| Part | what it is | $price | <a href="https://www.adafruit.com/product/3686"> Link </a> |
```

# Starter Project

<iframe width="560" height="315" src="https://www.youtube.com/embed/9fetkc7HMbk?si=WrSm_SIhvWVOaIxo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

My starter project is a retro arcade console. The console has 5 levels of games that can be played. The red button is used to start and switch off the console. The 4 buttons on the bottom left are for movements in every direction. The top yellow button on the right rotates pieces and begins the game. This is a fun portible game.

I chose this as my starter project to enhance my skills in soldering. The project helped me learn how to make proper cone-shaped joints and practice with multiple pieces. Some of the joints were very small and close together, making it challenging to solder it without a short circut, or connecting two close-by pins. This helped me practice soldering with pins and pads of various sizes and enabled me to practice advanced soldering skills.

# Starter Components

![Headstone Image](364C49C2-2689-4218-B72A-F74B93D8D0AA.png)

[Schematics link](https://www.hackster.io/lewisdiy/build-your-own-game-console-kit-play-the-classic-games-5ca95f)

| **#** | **Part** | **#** | **Part**|
|:--:|:--:|:--:|:--:|
| 1 | 1 Buzzer | 11 | 6 Buttons |
| 2 | 1 Electric Capacitor | 12 | 6 yellow button caps |
| 3 | 1 Micro USB | 13 | 1 PCB |
| 4 | 1 Power Cable | 14 | 8 M3x5mm Screw |
| 5 | 1 Switch | 15 | 2 M3x8mm Screw |
| 6 | 1 Red Switch Cap | 16 | 1 AAA Battery case |
| 7 | 1 Digitron display | 17 | 1 Acrylic shell |
| 8 | 1 IC Chip |  |  |
| 9 | 1 IC Socket |  |  |
| 10 | 2 LED dot matrix modules |  |  |


# Other Resources/Examples

- [Starter project parts](https://www.hackster.io/lewisdiy/build-your-own-game-console-kit-play-the-classic-games-5ca95f)
- [IoT pollution monitor guide](https://learn.adafruit.com/diy-air-quality-monitor/overview)

```HTML
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
```
