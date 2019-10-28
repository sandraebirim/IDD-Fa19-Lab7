# Video Doorbell, Lab 7

*A lab report by Sandra Ebirim*

### In This Report

1. Upload a video of your version of the camera lab to your lab Github repository
1. As usual, update your class Hub repository to add your [forked IDD-Fa18-Lab7](/FAR-Lab/IDD-Fa18-Lab7) repository.
1. Answer the questions in-line below on your README.md.

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**

[Hello You](https://www.youtube.com/watch?v=yMqHAvH0Yzs&feature=share)

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**

In order to enable the web camera, there was an addition of socket.emit('takePicture').

**b. Include a video of your working video doorbell**

[Video Doorbell](https://www.youtube.com/watch?v=IBOkcni5nNI&feature=share)


## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**

I first attempted to you the cartoon gimp nmp package. After installing the packages as instructed, I was unable to find the folders the instructions referred to after searching extensively as well as using terminal to look. 

I then attempted to use the jimp npm package. However, despite numerous different tries, I was unable to get this to show the altered image because it kept saying that the original image did not exist. I tried adding in and removing different components of the name as well as moving around the io.emit function that was intended to emit the altered image but it just repeatedly failed to work. 

**b. Upload a video of your working modified project**

[Broken Modified Project](https://www.youtube.com/watch?v=iE3oAQzcZ8Y&feature=share)
