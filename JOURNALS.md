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

Secondly, another tedious task I had to overcome was finding all of the data sheets and wiring data for each component! A major example was the EWAWGIB barcode scanning module. While I was trying to figure out how to wire its TTL interface, I realized it used a ribbon cable (thanks a lot, EVAWGIB 🙄). So, I had to find two things: a converter that would convert the ribbon cable's pins into the standard 2.54mm spacing, and diagram on what pins needed what to run the EVAWGIB safely. Thankfully, I found both of these after around 5ish minutes (look in the images for the diagram and the BOM for the converter)!

### Images
Here's the images for the diagram I made, as well as other images of diagrams and other miscellaneous images:

The full diagram:
<img width="1573" height="904" alt="Screenshot 2026-08-30 at 12 36 24 PM" src="https://github.com/user-attachments/assets/29707a1e-c3b0-40ed-b7ef-6f86570ff3f2" />

The wiring part of the diagram:
<img width="2033" height="907" alt="Screenshot 2026-08-30 at 12 37 11 PM" src="https://github.com/user-attachments/assets/28d9042b-a1bf-4ba8-aebf-641e181bdadf" />

(A very bad) CAD design:
<img width="1208" height="600" alt="Screenshot 2026-08-30 at 12 37 35 PM" src="https://github.com/user-attachments/assets/fd8a274f-a888-46a0-bc05-cdf5cbd433d0" />


The diagram I found (hallelujah!!!):

<img width="750" height="1632" alt="image" src="https://github.com/user-attachments/assets/f8d6fac6-2de4-4877-980d-c097a5797ab0" />

### Links
Here's some of the links to the things I've created so far:

The Design Whiteboard: https://miro.com/app/board/uXjVHwO0I8I=/?share_link_id=880799899556

### Total Hours Spent: 4.5 Hours


