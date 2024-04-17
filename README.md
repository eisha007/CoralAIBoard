# CoralAIBoard
Preliminary research on Coral Dev Board Mini for Angrave Research Group at Illinois

Beginning Requirements:
- Device running Linux OS or Mac
- USBC cable (power supply)
- USBC-A cable (device connection)
- WiFi connection

Dev Tool Installation:
- From terminal on device
  - python3 -m pip install --user mendel-development-tool
    NOTE: You might see the below warning get generated. 
    <img width="768" alt="Screen Shot 2024-04-17 at 6 45 07 PM" src="https://github.com/eisha007/CoralAIBoard/assets/49347262/639876a3-b24d-4086-9b25-5e9bbf74cab0">

    Run the following commands - in order - to get rid of this issue.
    - echo 'export PATH="$PATH:$HOME/.local/bin"' >> ~/.bash_profile
    - source ~/.bash_profile

  - Following this, if you rerun 'python3 -m pip install --user mendel-development-tool', you should see all requirements marked as "satisfied" - ensuring that your tool installed correctly
 

Board Powering:
- Orient the board such that the pin headers are at the top, and the USBC ports are at the bottom
- Connect the left USBC port to power
  - You should see a green LED flash on
- Connect the right USBC port to your device
  - The green LED should still be on
- To power on, press firmly on the power button, which is to the left of the left most USBC port
  - The green LED should momentarily turn off, and then turn back on again
  
  <img width="305" alt="Screen Shot 2024-04-17 at 6 53 07 PM" src="https://github.com/eisha007/CoralAIBoard/assets/49347262/2d91851b-56b0-44f1-a3c1-e7a6144ca42c">

