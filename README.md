->Introduction
We can use the WebRTC API to capture still photos using the device camera in Javascript.
Here we will stream video from webcam or the device's camera, and how to capture a still photo that can be used for any purpose like uploading to the server, etc.

In the HTML code, we will define a section for streaming the video captured from the camera, where the user will see their live video, to pose, 
and finally capture a photo.

We will have a Take Photo button, which will trigger the photo capturing.

And another section in which we will display the output. In that section, we will have an empty <img> tag, in which we will add the output image.

->Time for some Javascript

The Javascript code is divided into 3 sections.

The basic setup

Clear the photo

Capturing the photo

The Basic setup
The basic startup part which involves initialization of variables, asking the user for permission to access the webcam, 
then start video streaming from webcam, getting references to all the HTML elements which we will be using in the Javascript code, etc.

And we will be adding a click event listener to the Take photo button.

->Clearing the Photo

In this, we collect the frames of the photo from the canvas and then convert it into a format like PNG or any other to show it in the HTML page.

