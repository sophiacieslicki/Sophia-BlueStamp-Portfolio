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

<iframe width="560" height="315" src="https://www.youtube.com/embed/JMtBTNYhmgg?si=7giFy6QlRSh-T_qE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br>

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

<br>
&emsp; &emsp; My main project requires using Edge Impulse to create a machine learning model. Edge Impulse is an online platform where users can create and deploy their own machine learning models. My first milestone was to get familiar with the Edge Impulse interface by completing an audio speech classifier model in order to gain a deeper understanding of how machine learning works as I will use this later. 
<br>
&emsp; &emsp; My final model had 7 classes: hello_dad, hello_frederick, hello_nella, hello_sophia, hello_mom, noise, and unknown. The model works by having the user say something into a microphone. If the user says anything, the model continuously predicts the class and accuracy. The ideal accuracy for a machine learning model is 100%. Although, since I am not able to collect every single possibility of data in my data set, a realistic accuracy for my validation set is 80%. Machine learning uses a train dataset to train the model and a validation set in order to get an unbiased assessment of the accuracy of the model. **Figure 1** shows a test deployment of my model in real time. This illustrates that my model generated the correct class that I spoke in the microphone with an accuracy between 88% and 91% across 2 timestamps.
<br>
&emsp; &emsp; One of the challenges that I had to overcome when adding new classes was data bias. I originally had only had 3 classes: hello_sophia, noise, and unknown. Before adding new classes, it would correctly identify hello_sophia. However, it would incorrectly identify the new classes as hello_sophia because that was where the most data was. I was able to overcome this problem by adding more data to the classes that lacked sufficient data. Since I can't generate a graph showing the accuracy of the training and validation datasets overtime, I can't determine if the data was underfit or overfit. However, **Figure 2** shows the confusion matrix for the validation set that Edge Impulse generates. Looking at the matrix, my model was able to identify noise correctly 97.6% of the time. However the class with the lowest percentage was “hello dad”. The model was only able to correctly identify this class only 76.8% of the time which is still fairly high. Therefore, something that I can do in order to improve my model for the future is add more data to my “hello dad” class. The confusion matrix shows that the model was able to correctly predict the individual class accurately. The highest inaccuracy in the matrix is when the model predicted hello_mom but the actual label was hello_nella. Although, the model only predicts the inaccuracy between hello_mom and hello_nella 9.3% of the time which is very low.
<br>
&emsp; &emsp; Something that I learned in this milestone was data splitting. One reason why data splitting is important is that long recordings of a class can have noise which leads to inaccurate data and low accuracy. **Figure 3** illustrates how I split the data on Edge Impulse. When I was recording the training data for my model I used recordings that were 1-3min long with me repeating the words associated with the class over and over again. This led to a low accuracy because the model wasn’t able to determine specifically when I was saying the class. In order to overcome this challenge I split my recordings. Splitting into small manageable chunks on Edge Impulse helped me organize each individual set of data so that it has a train/test split of 80/20 respectfully. 
<br>
&emsp; &emsp; In order to visualize how Edge Impulse Works, **Figure 4** is a flow chart that shows the process of how I used Edge Impulse in order to create my model.
<br>
&emsp; &emsp; Overall, through doing this tutorial I learned a lot about machine learning and how to use Edge Impulse and improve models and data. I am excited to implement what I have learned into my Fitness Rehab device.

<br>

![Headstone Image](Milestone1_Figure1.png)
<br>
**Figure 1:** This is a live test of my machine learning model through Edge Impulse. I said “hello frederick” into the microphone of my computer and the model responded by showing the hello_frederick class and guessed this with an accuracy of 88% and 91% between timestamps.

<br>

![Headstone Image](Milestone1_Figure2.png)
<br>
**Figure 2:** This image shows how my validation set performed through a confusion matrix. The actual values are in the column on the left and the predicted values are in the row at the top of the confusion matrix. Looking at this confusion matrix, something that I can do to improve my matrix for the future is add more data for the hello_dad label in order to increase its accuracy on the confusion matrix.

<br>

![Headstone Image](Milestone1_Figure3.png)
<br>
**Figure 3:** This is how I split my data recording on Edge Impulse. This recording was originally 2min. I was able to split the data by zooming in on the individual waveforms. I added segments in order for Edge Impulse to understand specifically what parts of the audio I needed to split. After splitting the recording, I was able to turn this 2min recording into 1-2 sec data sets. 

<br>

![Headstone Image](Milestone1_Figure4.png)
<br>
**Figure 4:** Flowchart created through Lucid Chart in order to illustrate how I used Edge Impulse to create my machine learning model. The category transfer learning is when I use a pre-existing model but train it for a new task. I used MobileNet as my pre-existing model and changed the final dense layer in order for the model to do my task.

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
&emsp; &emsp; I chose Weevil Eyes as my starter project because I wanted to gain a basic understanding of some of the fundamental electrical components used in electrical engineering. When pressing my finger on the photocell of my Weevil Eyes project, the light emitting diodes (LED’s) light up and when I remove my finger from the photocell the LED’s go dark. 
<br>
&emsp; &emsp; The components of my Weevil Eyes are a Weevil Eye Circuit Board, 2 LED’s, a 47K resistor, two 220K resistors, a Bipolar Junction Transistor (BJT), a photocell, a battery holder, and a 20mm battery. A photocell is a light sensitive resistor: as light increases, the resistance decreases and vice versa. **Figure 1** shows that the voltage of the battery (3V) remains constant and the current depends on the resistance of the photocell (R4 in **Figure 1**). Basically R4 and R3 form a voltage divider which controls the voltage of the base. **Figure 2** shows the BJT.
<br>
&emsp; &emsp; There are three BJT components: 1) collector, 2) base, and 3) emitter. The collector is connected to ground, the base is connected to the photocell, and the emitter is connected to the resistors and LEDs, all shown in **Figure 1.** The resistors restrict and regulate the electrical current. When your finger is removed from the photocell, there is resistance and the electrical current cannot pass through the collector and emitter. This means that the circuit is an open circuit and the LEDs won’t turn on.
<br>
&emsp; &emsp; I am excited to begin my Fitness Rehab Device as my main project and strengthen my electrical engineering skill set.


![Headstone Image](Figure1_WeevilEyes.png)
<br>
**Figure 1:** Schematic showing Weevil Eye circuit. R4 is the photocell and is the only sensor. This controls the LED lights.
Source: https://www.youtube.com/watch?v=Az2TM6Gtp0o
<br>
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
