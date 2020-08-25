# MongoDB
- [Install](#install)
  
  
---

## Install
###### MacOS
```sh
brew update
brew install mongodb
brew services start mongodb
# if there is some error message
# type homebrew command 
brew doctor
```
  
###### Window/Linux
https://www.mongodb.com/download-center/community  
  
## Comman
###### run database
```sh
# on installed directory (default)
mongo 
```
  
###### add system variable (on Window)  
```sh
# if you want to use this shell command wherever freely
# you must set-up environment variable path (on Window)
# [myPC] => mouse right click 
# [advanced system setup] click 
# [system variable(N)] click
# [system variable(S)] click
# (in list) select named 'Path'
# below [Edit(I)] click
# [New(N)] click
# "add" mongodb installed path
# ex) C:\Program Files\MongoDB\Server\4.2\bin
```
  
###### check version
```
mongo --version
```
  
## Mongoose
