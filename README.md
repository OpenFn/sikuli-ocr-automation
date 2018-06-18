# sikuli-ocr-automation

### to be ansible-ized
First provision an ubuntu 16.04 box on digital ocean, then ssh onto the server.
Run:

#### pre-reqs
`apt-get update`  
`apt install xvfb`  
`apt install libopencv-dev`  
`apt install tesseract-ocr`  
`apt-get install openjdk-8-jre-headless`  
`apt install xinit`  

#### real screen
`sudo apt-get install gnome-core`  
`sudo apt-get install vnc4server`  
`vncserver` (set strong password, this will run on port 5901)  


#### sikuli
`mkdir sikuli && cd sikuli`  
`wget https://launchpad.net/sikuli/sikulix/1.1.2/+download/sikulixsetup-1.1.2.jar`  
