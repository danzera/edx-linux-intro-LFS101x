Two options for using Linux:  
**Command Line Interface (CLI)**  
Text input interface. Efficient for repetitive tasks.  
**Graphical User Interface (GUI)**  
Easier to navigate if you don't remember the programs/commands to perform a task, or do so rarely.

**Display Manager**  
A service that keeps track of the displays, loads the X server and manages graphical logins. If the display manager is not started by default, you can start the graphical desktop manually by running `startx` from the command line, or you can start the display manager (gdm, lightdm, kdm, xdm, etc).

**X Window System (X)**  
Loaded as one of the final steps of the boot process. Rather old software (80s). A newer system, **Wayland**, is gradually superceding it, and is the default in Fedora, RHEL 8 and other distros.
