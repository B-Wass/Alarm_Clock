# Fullscreen Clock with Alarm

  A simple fullscreen digital clock built with Python's `tkinter` module. Apart from just telling the time, the clock also has a basic alarm feature. There is also a menu full of customization options accessible by left-clicking.

## Features:

  **3 Versions**:

    V-4.0x: Round clock.

    v-4.1x: Round clock with audio file alarm. (coded for Linux)

    v-4.2x: Round clock with GPIO buzzer alarm. (coded for Raspberry Pi)

  **Fullscreen Clock**: Display time in a frameless window mode.

  **Interactive**: Click anywhere on the screen to close the application.

  **Custom Background**: Customize the background with an image of your own.

  **Set Alarm**: Incremental buttons to set hours and minutes for the alarm.

  **Visual Alarm**: A pop-up notification appears when the alarm rings.

  **Stop/Snooze/Reset Alarm**: Buttons to stop and keep the previous alarm, stop and snooze the alarm, or stop and reset the alarm.

## Prerequisites:

  **Python 3.x**

  **tkinter** module (typically comes pre-packaged with Python standard distributions).

## Installation:

  1. **Clone the repository and navigate to the directory**:

    ```
    git clone https://github.com/B-Boone/Alarm_Clock
    cd Alarm_Clock
    ```

  2. **Install dependencies**:

    ```
    pip3 install tkinter
    ```

  3. **Move alarm.wav and image.png files to home directory**: Only for V-4.10 (audio version)

    ```
    mv ~/Alarm_Clock/alarm.wav ~ && mv ~/Alarm_Clock/image.png ~
    ```

## How to Use: 

  1. **Run the Application**: Make sure to use the correct version number! Check the version number of the file you want to use, as we are now on version number 3.x0!

    V-4.00
      ```
      python3 clock_V-4.00.py
      ```

![2023-09-29-112542_1920x1080_scrot](https://github.com/B-Boone/Alarm_Clock/assets/101531474/4300af78-4376-4d57-8db2-e8a3c194d26f)

    V-4.10 & V-4.20
      ```
      python3 clock_V-4.10.py
      ```
      python3 clock_V-4.20.py
      ```

![2023-10-03-104239_1920x1080_scrot](https://github.com/B-Boone/Alarm_Clock/assets/101531474/6c2c4981-83bd-4ed7-adcf-7ea2d02f100a)

  2. **Set the Alarm**: Click the 'Set Hour' and 'Set Minute' buttons to set the alarm.

  3. **Alarm Notification**: A pop-up will appear when the alarm rings. Press the stop button to stop the alarm and keep the previoulsy set one, press the snooze button to stop the alarm and have it go off again in 5 minutes*, or press the reset button to stop the alarm and clear the previously set one.

    * This can be adjusted under the left-click popup menu
    
![2023-10-11-224403_1920x1080_scrot](https://github.com/B-Boone/Alarm_Clock/assets/101531474/0a88ea53-1ad6-41d6-985b-d287c105d0de)

  4. **Exit**: Click anywhere on the clock to exit the program.

## Structure:

  **Clock Class**: Inherits from `tk.Tk`.

    - Has methods to draw the clock hands, hour marks, numbers, and check the alarm.

    - Contains button commands to set the alarm hour and minute.

## Possible changes:

## Contributing:

  Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License:

  **[MIT](https://choosealicense.com/licenses/mit/)**

---

## *ENJOY!*
