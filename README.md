# TTC Bus Buzzer
A ESP32-based project to have a quick way to see when to expect buses around my apartment, ideally on a seven segment display when I push a button.

### Scope
There are two bus stops near me that both have multiple routes that will take me to the nearby subway station which is my destination 99% of the time. This means my system will have to go though multiple routes at each stop to get all the predictions. It will then sort these at each stop in order and eliminate any that are too soon to catch or too far to matter.

### Progress
- [x] Get API requests working with the TTC
      - [ ] Figure out why I had to hardcode the agency parameter
- [x] Group and sort the responses by stop
- [ ] Setup and test 7 segment display
- [ ] Design a custom PCB for this
