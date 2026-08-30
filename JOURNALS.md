# Journals
Hey! I'm Ayaan, a 13 year-old who's spend ~1.5 years on Hack Club! This is where I'll post all of my journals, specifically made for the program [Gadget Market](https://gadget.hackclub.com).

## 8/25/26
### A Summary Of What I Did Today
Today, I didn't build or CAD anything! Instead, I focused primarily on designing the Bathroom Pass using [Web Whiteboard](https://webwhiteboard.com)!
The diagram includes the wiring diagram, the links to all of the parts via AliExpress, and a small CAD diagram showcasing some useful images of the to-be CAD. 
I've tried to be as accurate as possible with the wiring, even color-coding the wires and creating pins to connect them to!

### Researching
After about 20 minutes of researching, I found three very important parts: 
- A barcode scanning module (without the traditional external handle and button configuration, EVAWGIB DP08)
- An ESP32-C3 (which had all the necessary pins and antennas, thankfully including WiFi and Bluetooth)
- A 360 degree servo (EMAX ES08-MD)

The barcode scanner would scan the barcode on the ID and lower the ID while the person went to the bathroom, while the ESP32-C3 would emulate a keyboard (using Bluetooth) to give the person a hall pass (using the 5starstudents software).
Then, once the person came back, they would click a button, which would emulate a keyboard to check the person out and simultaneously give the ID back to the person!

I also had to go through various data sheets and diagrams to figure out how to wire all of the components together!

### Problems And Tedious Tasks
Wow, I sincerely wish this section didn't exist! However, we all encounter these in some parts of our designing process.

Firstly, one of the major tedious tasks of the building process was finding all of the parts on AliExpress. Sure, there were lots of listings for the parts I needed, but I was struggling to find good prices for the parts. Thankfully, after around 10ish minutes, I was able to find three listings that would allow my project to cost less than 30 dollars! They will all be in the BOM, as well as [on the whiteboard I used](https://miro.com/app/board/uXjVHwO0I8I=/?share_link_id=59015536251). 

Secondly, another tedious task I had to overcome was finding all of the data sheets and wiring data for each component! A major example was the EWAWGIB barcode scanning module. While I was trying to figure out how to wire its TTL interface, I realized it used a ribbon cable (thanks a lot, EVAWGIB 🙄). So, I had to find two things: a converter that would convert the ribbon cable's pins into 
