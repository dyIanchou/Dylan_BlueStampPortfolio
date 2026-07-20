# Browser Controlled Robotic Arm
<!--Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails! -->

My project was a browser controlled 4-axis robotic arm that is controlled by a controller. It consists of an arduino and a 7.5 volt battery to power 4 servos that control rotation of the base, the joints of the arm, and the opening and closing of the claw at the end. From this project, I learned power systems, how to use and encode an arduino, as well as learn valuable insight into proper tactics for building in compact spaces with a large range of motion. 

<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Dylan C | Menlo-Atherton | Mechanical Engineering | Incoming Senior


![Headstone Image](Dylan_C_(2).jpg)

 <!--- 
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE
-->

# Third Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Since the last milestone, I was able to build a website that is actually capable of connecting to my robotic arm and controlling it. I made my website through Visual Studio Code through HTML CSS and JS. Using the built in ability to send data through COM ports, I was able to send signal via an established bluetooth conneciton to the HC-05 on my robot. However, there was a lot of issues when trying to establish a strong and stable connection. In addition, my claw seemed like it was too weak to grab anything with any real mass to it. To solve the issue of connectivity, I looked further into making my code require less of a stable connection. Instead of checking if the button is being pressed each millisecond, I changed it to send a signal to start moving a joint when I pressed a button, and a signal to stop when I let go. This way, a command that might have needed dozens of data signals was reduced to only 2. Another way I fixed the issue was reworking the power system. I realized that the amount of amps I was using to power my entire system wasn't enough, causing the bluetooth module to power off occasionally and disconnect from the website. I fixed that by changing my battery arrangement to provide more amps so that my HC-05 would not power off anymore. To fix my claw grip strength, I filed down the claws to give more surface contact between the object and the claw, as well as applying a few layers of plasti-dip to increase the grip. I also replaced the servo with one that could apply a larger torque. Through the making of this project I learned how power systems work and why it is important to pay attention to voltage and current. I also learned how to code in multiple languages, such as C++ and Javascript, as well as how to use and program microcontrollers for projects. For additional modifications, I hope to add a live video stream of the claw's view visible through the website.



# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/p3D43LfJSFU?si=gwQ2DV2B8oTpEN7N" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Since my first milestone of getting all the hardware assembled and installing basic instructions onto the arduino, I have done a lot of modifications to the arm so that it works with bluetooth control through my computer. Since I am using the arduino nano, the microcontroller doesn't have any inherent bluetooth capabilities, I had to attach this HC-05 as a bluetooth module as a reciever to send data from my computer to my arduino. I also made some rough code to test that the information I send through the terminal is reaching my robotic arm by adding simple controls to rotate, move, and open/close the arm. Some challenges I faced were that I struggled to connect my HC-05 to my computer using a terminal, because that is something I have never done before. I have learned a lot about how bluetooth works and how to use my computer to communicate with external devices. Some future steps will be to construct the website with buttons that can control the robot instead of sending stuff directly through the computer terminal as well as maybe changing the claw design to increase grip strength and flexibility.

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/L1J3GDKKwVk?si=W5kasQpIThyePsi1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
My project is a browser controlled robotic arm, where the final goal is to build an arm that will respond to inputs sent from a website to pick up a large variety of robots. So far, I have tested all of the servos I will be using in my project and assembled the first joint of my arm, the swivel base, and a location for my arduino to stay secured to the arm. I have been having difficulties with controlling the speed of the servos through sketches on the arduino, and plan on fine tuning my code later on. 

# Starter Project


<iframe width="560" height="315" src="https://www.youtube.com/embed/MPqgOHRAKvI?si=1JG-JZ17lmMe7f-Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

My starter project was the Jitterbug, which was a coin battery connected to a switch. The switch powered two red LEDs that were purposed as eyes as well as an unbalanced coin motor which when powered will vibrate the Jitterbug, providing movement. While building the Jitterbug, I learned how to solder and best practices to create a solid and neat joint between electrical components. Along the way, I made several mistakes with the soldering iron and accidentally creating a short circuit, causing me to spend a lot of time removing it with the desoldering pump. I think in the future if I was to continue working on this project I would try to creat neater soldering joints.

<!--
# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 
# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 
c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}
void loop() {
  // put your main code here, to run repeatedly:
}
-->

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 
| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| DSD Tech HC-05 Bluetooth Module | Connecting computer to arduino | $9.99 | <a href="https://www.amazon.com/DSD-TECH-HC-05-Pass-through-Communication/dp/B01G9KSAF6"> Link </a> |
| Arduino Nano | microcontroller for servos | $13.99 | <a href="https://www.amazon.com/AYWHP-ATmega328P-Microcontroller-Compatible-Arduino/dp/B0DFGQW2ZY?th=1"> Link </a> |
| Micro Servos x4 | Presise control over joints | $7.98 | <a href="https://www.amazon.com/Micro-Servos-Helicopter-Airplane-Controls/dp/B07MLR1498?th=1"> Link </a> |
| AA battery x5 | Powering the arm | $6.49 | <a href="https://www.amazon.com/Amazon-Basics-High-Performance-Alkaline-Batteries/dp/B00O869KJE?th=1"> Link </a> |
| Smart Robotic Arm for Arduino | hardware/base arm | $46.99 | <a href="https://www.amazon.com/LK-COKOINO-Compliment-Engineering-Technology/dp/B081FG1JQ1"> Link </a> |



<!--
# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
-->
