# Fitness Rehab Device

This Fitness Rehab Device is targeted toward people with shoulder injuries more specifically athletes and musicians such as guitarists. Using machine learning, the device can track correct shoulder movements for shoulder recovery. If the user performs the correct shoulder exercises for recovery, the device will be able to detect this and fill a progress bar.

<!--- Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails! -->

<!---
<!---
You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML 
<!--- This is an HTML comment in Markdown
<!--- Anything between these symbols will not render on the published site
```
-->


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Sophia C | Mountain View High School | Biomedical Engineering | Rising Junior

<!---
**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**
-->

<img src="SophiaC_Headshot.jpg" 
     width="400" 
     height="500" />
  
# Final Milestone

<!--- **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.** -->

<!---
<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> 
-->

<!--- For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE -->



# Second Milestone

<!--- **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.** -->

<!---
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
-->

<!--- For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

-->

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/7U8yNla3_gU?si=KJVs3y6t1QKK2BAB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Schematics 
<!--- Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. -->

# Code
<!--- Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. -->
<!---
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
-->
# Bill of Materials
<!--- Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. -->

<!---
| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
-->

# Starter Project - Weevil Eyes

<iframe width="560" height="315" src="https://www.youtube.com/embed/GFcvl3yDpks?si=2sdZIt-8Nk4kHONy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<br>
I chose Weevil Eyes as my starter project because I wanted to gain a basic understanding of some of the fundamental electrical components used in electrical engineering. When pressing my finger on the photocell of my Weevil Eyes project, the light emitting diodes (LED’s) light up and when I remove my finger from the photocell the LED’s go dark. 
<br>
The components of my Weevil Eyes are a Weevil Eye Circuit Board, 2 LED’s, a 47K resistor, two 220K resistors, a Bipolar Junction Transistor (BJT), a photocell, a battery holder, and a 20mm battery. A photocell is a light sensitive resistor: as light increases, the resistance decreases and vice versa. **Figure 1** shows that the voltage of the battery (3V) remains constant and the current depends on the resistance of the photocell (R4 in **Figure 1**). Basically R4 and R3 form a voltage divider which controls the voltage of the base. **Figure 2** shows the BJT.
<br>
There are three BJT components: 1) collector, 2) base, and 3) emitter. The collector is connected to ground, the base is connected to the photocell, and the emitter is connected to the resistors and LEDs, all shown in **Figure 1.** The resistors restrict and regulate the electrical current. When your finger is removed from the photocell, there is resistance and the electrical current cannot pass through the collector and emitter. This means that the circuit is an open circuit and the LEDs won’t turn on.
<br>
I am excited to begin my Fitness Rehab Device as my main project and strengthen my electrical engineering skill set.


![Headstone Image](Figure1_WeevilEyes.png)
<br>
**Figure 1:** Schematic showing Weevil Eye circuit. R4 is the photocell and is the only sensor. This controls the LED lights.
Source: https://www.youtube.com/watch?v=Az2TM6Gtp0o

![Headstone Image](Figure2_WeevilEyes.png)
<br>
**Figure 2:** Schematic that shows how the Bipolar Junction Transistor (BJT) in my Weevil Eye project.

# Other Resources

- [MLU-EXPLAIN](https://mlu-explain.github.io/)

<!---
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
-->
