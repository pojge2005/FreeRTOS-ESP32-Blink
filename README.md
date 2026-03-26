# FreeRTOS-ESP32-Blink
“ESP32 FreeRTOS-based LED Blink project demonstrating task creation, scheduling, and dual-core execution.”
This project demonstrates the use of FreeRTOS on ESP32 to perform multitasking.

A dedicated task is created using xTaskCreatePinnedToCore() to blink an LED connected to GPIO 2. The task runs continuously with non-blocking delays using vTaskDelay(), allowing efficient CPU utilization.

Key Concepts Covered:
- FreeRTOS task creation
- Task scheduling
- Dual-core execution on ESP32
- Non-blocking delay (vTaskDelay)

Hardware Used:
- ESP32 development board
- Built-in LED (GPIO 2)

Output:
- LED blinks every 1 second
- Serial monitor displays task execution and core ID

Implemented a real-time LED control system using FreeRTOS on ESP32. Designed and deployed tasks with priority-based scheduling and core pinning to demonstrate multitasking and efficient resource utilization in embedded systems.
