# Stop Watch Application

Welcome to the Stop Watch Application! Keep track of time with precision using SysTick timer-based intervals.

## Features

Accurate Timing: The application utilizes the SysTick timer with interrupts to increment the elapsed time every second, providing precise time measurement.

Real-time Display: The HAL LCD driver is utilized to showcase the stopwatch's time in seconds, minutes, and hours on the display.

Pause and Resume: The application incorporates two switches for pausing and resuming the stopwatch functionality.

## Architecture Layers

### MCAL Layer (Microcontroller Abstraction Layer)

DIO Driver: Enables digital input and output operations, facilitating communication with external devices.

External Interrupts Driver: Manages external interrupt events, ensuring responsive interactions with peripherals.

SysTick Driver: Utilizes the SysTick timer to create precise time intervals, triggering interrupts on each second.

### HAL Layer (Hardware Abstraction Layer)

LCD Driver: The LCD driver controls the display, allowing the stopwatch's time values to be presented in seconds, minutes, and hours.

### Application Layer

The Application Layer manages the functionality of the stopwatch. It calculates the time values in seconds, minutes, and hours, coordinating their display on the LCD screen.

## Getting Started

1-Configure the SysTick driver to operate with one-second intervals for accurate timing.

2-Utilize the DIO and External Interrupts drivers for hardware interaction as required.

3-Implement the LCD driver to display time values on the screen.

4-Compile the C code and upload it to your microcontroller.

5-Run the application, and observe the stopwatch's time progressing on the LCD display.

Click the attached link to ensure successful execution by passing all test cases flawlessly.

https://drive.google.com/file/d/19AUZmpnLlWJFAJ9PHUwxLwlDEXGEA72p/view?usp=sharing

Misra C report

https://drive.google.com/file/d/1uqz-xzrr2Qwrx9szOzDn77j4kFENnlDi/view?usp=sharing

