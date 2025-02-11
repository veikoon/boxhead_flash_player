# boxhead_flash_player

Very simple player to host any swf file on any machine.  
All credits of [boxhead](https://www.crazymonkeygames.com/Boxhead-2Play-Rooms.html) game goes to crazymonkeygames.com and Sean Cooper his creator.  
The engine used to run flash game is [Ruffle](https://github.com/ruffle-rs/ruffle).  

## Build


Simply clone the project and run any webserver (python for example): 
```
git clone https://github.com/veikoon/boxhead_flash_player
python3 -m http.server 8080
```

Using Docker :
```
docker build -t boxhead .
docker run -p docker run -p 8080:80 boxhead
```
