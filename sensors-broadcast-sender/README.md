# sensors-broadcast-sender

Example of Raspberry Pi with SenseHAT running the **broadcastEntranceCW.py** script (see below).

![Image of Raspberry Pi with SenseHAT on TestDoor](https://github.com/kkremizas/count-trackula/blob/main/CountTrackulaWorking.gif)


During first-time installation:
- Run **broadcastEntranceCW.py** after you set up the Raspberry Pi with the SenseHAT in an Entrance door that opens clockwise.
- Run **broadcastEntranceCounterCW.py** after you set up the Raspberry Pi with the SenseHAT in an Entrance door that opens counter-clockwise.
- Run **broadcastExitCW.py** after you set up the Raspberry Pi with the SenseHAT in an Exit door that opens clockwise.
- Run **broadcastExitCounterCW.py** after you set up the Raspberry Pi with the SenseHAT in an Exit door that opens counter-clockwise.

![Image explaining clockwise and counter-clockwise opening of doors](https://www.doorfurnituredirect.co.uk/media/wysiwyg//Handing-FAQ/handingdiagram.jpg)

- Run **broadcast_random.py** if you want to broadcast a message containing either an Entrance or an Exit signal without the need to own a SenseHAT. This is to be used for testing purposes.

Here is an image of our a Raspberry Pi with SenseHAT on a physical prototype of a door used for testing purposes.

![Image of Raspberry Pi with SenseHAT on TestDoor](https://github.com/kkremizas/count-trackula/blob/main/pidoor.jpeg)
