# week5

<aside>
💡

Personal works

</aside>

made this container for arduino using 3D and laser cutting

![A7757580-CBB9-429C-AC0B-3D8303C78976_1_102_o.jpeg](week5%2011249e84537580e2817be4ab35955a29/A7757580-CBB9-429C-AC0B-3D8303C78976_1_102_o.jpeg)

<aside>
💡

Setting up and Getting familiar with Photon

</aside>

I missed last week class, so had hard time catching up

![CEAD1D54-1BE8-48E9-8CF8-424040132FB5.heic](week5%2011249e84537580e2817be4ab35955a29/CEAD1D54-1BE8-48E9-8CF8-424040132FB5.heic)

![FB86BB31-46B5-4384-B927-F42CFA91CEBA.heic](week5%2011249e84537580e2817be4ab35955a29/FB86BB31-46B5-4384-B927-F42CFA91CEBA.heic)

I had some problems installing particle -cli… 

I worked on it with TA and (ChatGPT) and was able to solve the problem. 

![60570B87-5A7A-49C0-86F2-3C9CA2A28AB8.heic](week5%2011249e84537580e2817be4ab35955a29/60570B87-5A7A-49C0-86F2-3C9CA2A28AB8.heic)

<aside>
💡

**Homework: Building your first system part 2**

</aside>

Working on this project gave me the opportunity to explore the core principles of system building through hardware interaction and embedded programming. The task of making an LED blink in response to a button press, while seemingly simple, provided several learning moments and deepened my understanding of timing, interrupts, and system states.

## code

![image.png](week5%2011249e84537580e2817be4ab35955a29/image.png)

(forgot to take a picture before I disassemble…. 😞)

(I will redo it and attach picture later)

- **Process and Circuit Setup:**
    - Assembled the Photon Particle, button, and LED.
    - Configured button with a pull-down resistor to avoid floating signals.
    - Implemented basic code for LED blinking in response to button press.
- **Key Learning Moments:**
    - **Interrupts:** Learned how hardware interrupts respond immediately to input without continuous polling.
    - **Random Blink Rate:** Successfully randomized LED blink rate by modifying the `periodicity` variable.
    - **Debouncing:** Realized the need for debouncing to prevent multiple button triggers from mechanical noise.
- **Challenges:**
    - Balancing timing between button presses and LED blinking.
    - Missed button presses initially due to interference with delays.
- **Possible Expansions:**
    - Adding a motion sensor to control blink speed based on movement.
    - Using machine learning to recognize button press patterns and change the system’s response.
- **Conclusion:**
    - Gained insights into system timing, interrupts, and user interaction.
    - Excited to expand the system with sensors and machine learning in future projects.
 


<aside>
💡

Reflection

</aside>

- **What I Learned**

    - Understood how hardware interrupts improve system efficiency over continuous polling.
    - Gained insight into managing timing and delays to avoid interference between tasks (LED blink and button press).
    - Recognized the importance of debouncing to improve button handling.
    - 
- **Current State**

    - System works as intended but could benefit from adding debouncing and optimizing timing.


<aside>
💡

Speculations

</aside>

- **Future Directions**
    - Add sensors (e.g., motion sensor) to make the system more interactive (e.g., changing blink speed based on movement).
    - Incorporate machine learning to recognize user patterns and predict actions.
 
- ** Industry Relevance**
    - Similar to Philips Hue lighting system, which adjusts based on user activity and sensors, this project could evolve into a smart, predictive lighting system.
