# Aqueous

https://github.com/user-attachments/assets/dc7b21fd-ac8a-490e-9593-20b88dcd2f78

## Instructions for Use:

On macOS, open the webpage [https://stelladrinkwater.github.io/Aqueous/] in Chrome (other browsers may not work). Then, set up the IAC Driver (see below for step-by-step instructions with images). 

On Windows or Linux, you’ll need a virtual MIDI port such as loopMIDI (Windows) or rtpMIDI/a2jmidid (Linux). Windows and Linux setups remain untested as of this iteration of the project. 

Once your virtual MIDI port or IAC driver is ready, load one of the included sampler patches (Logic and Ableton versions available, please open a request in the issues tab if you would like to see another format, such as Kontakt or Decent Sampler) from the project repository, and set up a MIDI track in your DAW to listen to that virtual MIDI port for notes. 

Velocity is mapped to bubble size and pitch spans an arbitrary 24–72 range (the sampler patch matches this). Notes are 300 ms long. Keep the browser window active (don’t close it, switch tabs, or let it sleep, or else MIDI data flow will stop).


### Instructions for Mac IAC Driver (Virtual Midi) Setup:

1. Cmd + Space search for Audio Midi Setup and open it
   
   ![Screenshot 2025-08-08 at 12 46 29 PM](https://github.com/user-attachments/assets/15ca6575-2c78-4403-ab94-e0876ab94f29)
   
3. Select the IAC Driver
   
   ![Screenshot 2025-08-08 at 12 45 02 PM](https://github.com/user-attachments/assets/6ac8a28e-912e-432a-87fd-5244222d2c18)
   
5. Check "Device is online", make sure at least one bus exists (use the "+" to add one if needed).

   ![Screenshot 2025-08-08 at 12 45 10 PM](https://github.com/user-attachments/assets/184c4590-3a77-4248-9876-6e735c9e1f57)

7. Select the IAC Driver as the MIDI device in your DAW


#### Notes:

Chrome is the only browser which I can confirm works. I have had issues with Safari and Arc.

Velocity will be proportional to bubble size.

24-72 midi range.

#### Assets:

Orca calls sound clip pulled from the Orca Behavior Institute:
https://soundcloud.com/orcabehaviorinstitute/september-13-2024-js-ks-and-ls-at-lime-kiln

Choir sample from GregorQuendel on freesound.org:
https://freesound.org/people/GregorQuendel/sounds/685055/

Font is:
https://www.fontspace.com/sailing-scribe-font-f126927

