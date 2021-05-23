# monte-carlo-python
Excel-Python Monte-Carlo simulation

This is a project to create open-source tool for Monte-Carlo simulation in Microsoft Excel.  
Currently available tools like SipMath or Model@Risk are unsatisfactory in that:
- all of them are propriatory, you cannot see or change the scripts;
- some are not free, and even free versions have limited functionality;
- free SipMath tool is OK, but it creates simulation data inside Excel worksheet, which may limit performance on big random data and should not be visible to users anyway

The idea is to use Python scripts as backend, using xlwings library.
This should help with programming Excel, and on the other hand with storing simulation data outside 
