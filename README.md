### radb

#### components
* host server
* host client
* remote client

#### role
##### remote client
* server ip, id setting
* connect to host server

##### host server
* listen to remote client
 * id : socket in memory map.

##### host client
* reigster id, then connect to host server

#### commands
* radb register : register current *nix id to host server (make connection)
* textual command
 * radb devices, radb shell ls
* binary comand
 * radb push, radb pull 
* interactive command
 * radb shell 