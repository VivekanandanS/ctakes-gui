# ctakes-gui
Dictionary Creator downloaded from http://ctakes.apache.org doesn't work expected , so I made this as seperate stand-alone. Eventhough gui-res.jar contained files required by Dictionary Builder , it kept throwing missing resource required . This codebase is contains dictionary builder and resource required . I hope somebody facing the same issue can make use of this .


1. Follow User Installation guide to download ctakes-x.x.x.bin.tar 
2. Extract it , copy jars in lib folder and add it build path, instead you can simply add ctakes dependencies to pom.xml (Since I had all dependencies all ready downloaded from http://ctakes.apache.org , I didn't add to pom.xml)
3. Please dont add ctakes-gui.jar and ctakes-gui-res.jar . Since all classes collide or reference classes from jar, and project already contains resources required
4. Just , run the project
5. I found this video to be useful to get started with dictionary creator https://www.youtube.com/watch?reload=9&v=4aOnafv-NQs 
