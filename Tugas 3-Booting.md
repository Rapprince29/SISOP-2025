
# Nama: Muhammad Yoga Ananda Satria

## NRP: 3124500036
### Kelas: D3 IT B

![image url](https://github.com/Rapprince29/SISOP-2025/blob/2a5ba4194a2d56727d23dfef2eb04b1f79897e5c/Tugas3-Flowchart-Booting-Computer.pdf)

1. **Power On**  
   When the power button or reset button is turned on, the power source will flow to the computer.

2. **Power On-Self-Test**  
   After the computer turns on, the boot process begins with POST. POST is an initial check process carried out by BIOS or UEFI to ensure that all hardware is functioning properly.

3. **Initialization BIOS/UEFI**  
   After the POST is complete, the computer initializes the hardware and determines the order of drives to be used to start the operating system.

4. **Find and Load Bootloader**  
   Next, the BIOS/UEFI looks for a boot loader on the devices listed in the boot order. A boot loader is a small program that loads an operating system into memory. This boot loader then points to the operating system.

5. **Load Kernel Operating System**  
   Once the boot loader is loaded, it loads the operating system kernel into memory. The kernel is the core of the operating system that manages the hardware and system resources. It functions by initializing hardware components, setting up the file system and memory management, and starting the main processes of the operating system.

6. **Initialization System and Services**  
   The kernel then begins the process of initializing the system and services required to run the operating system, such as loading hardware drivers and initializing services such as network management, security, and system logging.

7. **Login and Shell Initialization**  
   Once system services are running, the system enters the User login and Shell Initialization phase. At this stage, the operating system prompts the user to log in by entering a username and password. Once authenticated, the system loads the user's personalized environment, which includes settings, preferences, and configurations.

8. **Load GUI or Shell**  
   Once system initialization is complete, the graphical user interface (GUI) or shell (for command-line based operating systems) will load.

9. **Startup Application**  
   The operating system then loads applications or programs that are set to run automatically at startup. These can be background applications, utilities, or security software.

10. **System Ready to Use**  
    After all the booting processes are complete, the operating system will display the desktop or user interface and is ready to use. At this point, the user can start running applications and using the installed hardware.
