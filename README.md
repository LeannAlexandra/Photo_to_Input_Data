# Photo_to_Input_Data
Android App that takes a picture and send it to server (Kotlin), which use opencv to interpret the page and translate to input data (for calculating quote and physical weight, for now)

The Outline of the plan: create an android app using android studio and Kotlin to use phone camera to take a picture (in my specific case of an order sheet.)
Crop and shape the image to match a predefined form ( as all ordersheets have a predictable layout, once the new picture match the layout, I can read data in predefined blocks.
I can incorporate OPENCV to crop the picture to the frame, because only certain information is necessary from the sheet (ie. knowing only the location will be sufficient determine what stock it is, and then what the weight, price  is)



