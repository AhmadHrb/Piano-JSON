# Piano-JSON
Easy JSON Piano Notes to be used in the Pionet App.

Add a Piano Note by Pull Requests!

## Add a music note:
  ### Without code:
  
  Create an [Issue](https://github.com/AhmadHrb/Piano-JSON/issues) and include a picture of the music note. A developer will add it soon,
  
  ### With code:
  
  Make a pull request by following the way other files in repo work. and edit the notes.json with your note name.
 
 
 ## Syntax:
 
 ### notes.json
 
 This file includes the notes available with a description. Used for the home page of the app to provide the available notes.
 
 ### notes/name.json
 
 This file includes basic information about the music note (like name, types) and includes the music note in terms of numbers (defined as data) and those data are the buttons from Do to Si.  Where Do is 0 and Si is 6. If the button is before the middle of the Piano negative numbers can be used. (-0 for the previous Do, 0 for the middle Do).
 
 ## App
 
 The Pionet app will be available on Google Play Store and source code is available [here](https://github.com/AhmadHrb/pionet-flutter).
