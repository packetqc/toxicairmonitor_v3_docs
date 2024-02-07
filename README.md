# Demo
![](/docs/demo.gif)

# LED Status colors

| Image | Color | Module | Status | Description |
|--|--|--|--|--|
|![](/docs/blue.png)| BLUE | NETWORK | OK | Network activities: aquire, ping services and checks |
|![](/docs/yellow.png)| YELLOW | NETWORK | OK | Network setup connection<br>Network connection retry with services<br>Network checks |
|![](/docs/green.png)| GREEN | DEVICES | OK | Devices data captures |
|![](/docs/purple.png)| PURPLE | DEVICES | OK | Devices checks |
|![](/docs/cyan.png)| CYAN | HARDWARE | OK | Hardware checks |
|![](/docs/off.png)| OFF | GENERIC | OK | Off for next status activity |
|![](/docs/red.png)| RED | NETWORK | ERROR<br>OK<br>OK | Not connected to services (blink 10 times)<br>Uploading data (solid red light)<br>Data uploaded (blink 3 times) |
|![](/docs/white.png)| WHITE | SETUP MAIN<br>SETUP MAIN<br>LOOP MAIN | OK | Logger is starting (solid white light)<br>Network connection with services successful (blink 3 times)<br>Values reseted after successful upload of data to services (blink 3 times) |

# Structure
![](/docs/structure.png)
