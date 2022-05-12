# Lesson: Interaction Design

### First and Last Name: Michalis Chatzilyras
### University Registration Number: dpsd18132
### GitHub Personal Profile: https://github.com/Chatzilyras-Michalis
### Augmented Reality Personal Repository: https://github.com/Chatzilyras-Michalis/Augmented-Reality

# Introduction

# Summary


# 1st Deliverable
- (Cylinder) For starters i created a new a-entity for the cylinder with the code i found in a A-frame from resources and changed the radius and height based on what i thought was better looking for me.
(Sphere) I proceeded with same mindset as the cylinder coding and changed the radius only for the sphere.
- (Snow) For the addition of the snow i copied the code i found in npmjs and added the command visible="false".
- (Speech command,annayang)From the npmjs i added the annyang-speech-recognition component code
- (Speech-command) For the appearance and disappearance of the snow i added inside the a-entity of snow the speech-command_show and speech-command_hide.The snow appears when we say start and disappears when we say stop.The two lines of speech-command were found on npmjs below the command of annyang.
# 2nd Deliverable
- DPSD MARKER:Firstly i started by making a new (a-marker) for my DPSD ID ("DPSD18132") from [here](https://medium.com/arjs/how-to-create-your-own-marker-44becbec1105) and [here](https://aframe.io/blog/arjs/).Then i edited my marker from the application Affinity Designer to show the correct dpsd number and i made a new file .patt also from [here](https://aframe.io/blog/arjs/).
I procceded by adding (a-text)in my code from [here](https://stackoverflow.com/questions/50323583/display-text-inside-3d-box-using-aframe-aframe-ar) ,  [here](https://ar-js-org.github.io/AR.js-Docs/)  and  [here](https://levelup.gitconnected.com/simple-augmented-reality-ar-integration-with-a-frame-f625e9dc66b8).Through trial and error i edited the position and the color of the text. I added the Grogu image with the help of Google and made an (a-image) with the help of [this](https://stackoverflow.com/questions/47610133/display-png-image-file-with-ar-js-augmented-reality) page and [this](https://aframe.io/blog/arjs/) page.
- (H and O Project) By watching the video on the example many times i realized that the markers were made as barcode type.I had to add the binary code by combining the code from [here](https://ar-js-org.github.io/AR.js-Docs/marker-based/) and [here](https://aframe.io/blog/arjs/).The binary code was added to the beggining of the code.
  - (assets and blender) I made two new (a-assets) to set up the Hydrogen and the Oxygen which i made on blender and exported them as .gltf. The two letters that define which one is which were made on affinity designer and i added them with the help of [this](https://www.youtube.com/watch?v=r5YNJghc81U&list=PLSMwPLroTXpBAptfsnWC95GM438Snk0IK&index=3) video and i confirmed that it was correct by watching [this](https://www.youtube.com/watch?v=jLGWE335J28) video and the help of [this](https://www.youtube.com/watch?v=IF9juYtbyoI&list=PLSMwPLroTXpBAptfsnWC95GM438Snk0IK&index=2&t=411s) video.I edited the texture to find the proper dimensios for the hydrogen and the oxygen by inspecting the sources of **Animation** from this [link](https://stemkoski.github.io/AR.js-examples/index.html?fbclid=IwAR3rNAQHrtUZ_n_ZzdC1NlWbWdfqfk39BByAimab6U210yrv7FDFGMxTb4I). 
- (H2O) As i did before with the assets of Hydrogen and the Oxygen i made a new asset for the H2O.I also edited it on blender with the help of the previous links and i followed the same procedure to export it.
- (Hydrogen and Oxygen marker)I made two new markers  (**a-marker**) from the code of [this](https://aframe.io/blog/arjs/) link ; i edited them on affinity designer by adding a barcode for each one which i found from [here](https://github.com/nicolocarpignoli/artoolkit-barcode-markers-collection).The value of each marker was defined by the barcode which i chose to set them.I added for both of them an (**a-image**) inside their markers to show for each individual the correct photo.The rotation ,geometry and height was edited to overlap the barcode.To call in the assets of hydrogen and oxygen i added inside the marker an (**a-entity**) and i edited the position and the scale to fit better.The gltf and animation rotate was found in [this](https://stemkoski.github.io/AR.js-examples/index.html?fbclid=IwAR3rNAQHrtUZ_n_ZzdC1NlWbWdfqfk39BByAimab6U210yrv7FDFGMxTb4I) link.(**note** i had to name id many things )
- (H2O position)Inside the  marker of oxygen i added an (**a-image**) to call the asset of H2O and added the visible=false because it had to appear only if the hydrogen and oxygen were on a certain distance of each other.(* the markers of oxygen and hydrogen have visible=true)
- (Adding the Marker distance)I added the **Script** code from [here](https://stackoverflow.com/questions/61239107/how-to-get-marker-position-x-y-ar-js) and edited the code to fit my markers.Lastly i added an if-else in order , if the distance(markerdistance) of the hydrogen and oxygen is smaller than 2 it has to show the H2O marker(**MarkerDistance<2**) and hide the other two  and if the distance is bigger than 2 it has to show the other two markers(markerdistance>2) and hide the H2O.
(**note** the entity of the marker distance had to be added before the markers of oxygen hydrogen and h2o)

# 3rd Deliverable 


# Conclusions


# Sources
- Del1
[Sphere,Cylinder](https://aframe.io/docs/1.3.0/components/geometry.html#cylinder#)
[Snow-code](https://www.npmjs.com/package/aframe-particle-system-component)
[Speech-command](https://www.npmjs.com/package/aframe-speech-command-component)
- DEL2
 [AR.JS](https://medium.com/arjs/how-to-create-your-own-marker-44becbec1105)
 [A-Frame](https://aframe.io/blog/arjs/)
 [AR.JS](https://ar-js-org.github.io/AR.js-Docs/) 
 [LevelUp](https://levelup.gitconnected.com/simple-augmented-reality-ar-integration-with-a-frame-f625e9dc66b8)
 [StackOverflow](https://stackoverflow.com/questions/47610133/display-png-image-file-with-ar-js-augmented-reality)
 [Youtube](https://www.youtube.com/watch?v=jLGWE335J28)
 [Stemkoski](https://stemkoski.github.io/AR.js-examples/index.html?fbclid=IwAR3rNAQHrtUZ_n_ZzdC1NlWbWdfqfk39BByAimab6U210yrv7FDFGMxTb4I)
 [GitHub](https://github.com/nicolocarpignoli/artoolkit-barcode-markers-collection)
 Blender


