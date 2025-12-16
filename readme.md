Example of how the formating will look

https://main_website?file=https://example.com.swf
  //read the end of teh link/the file format save to var P
  //check if P is a valid file format from list of supported file formats if not then just display that "invalid file url please try again"
  //if is a valid file format then redirect user to https://main_website/"P"?file=https://example.com.swf
      
https://main_website/"P"?file=https://example.com.swf
  //display the file in the proper ui for the format
  //swf show the animation or game in the ruffle emulator display
  //mp3/audio show a progress bar and play pause restart and make the progress bar dragable + a input specific time feild
  //mp4/video same as audio but also a video display area
  //html just open a new page but the html code is converted to a document url
  //other i will have to think about this one for a bit
