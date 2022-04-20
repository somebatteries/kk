# Knock Knock
# TODO:
- How to train custom YOLO models?
    - Realtime training:
        - Create a network that is trained just barely on known
        vehicles, but well trained on unknown vehicles, using COCO
        - Implement application code to run the detector
        - If an unknown vehicle is detected:
            - save the image as training data in a folder on the device
            - Notify user of unknown vehicle
            - Present option to label this vehicle as one of the known
              vehicles, moving it into the folder for that class label
            - When user labels the vehicle, do a fit using that sample( ** how the hell do i do that )

    - Could use labelLMG?
        - But this requires hand labelling.
    - Record stock footage of the desired vehicle (keeping it centered)
        - Use stock yolov3 find vehicles
        - for each frame
            - for each vehicle
                - compute the distances to the center of the image
            - select the vehicle closest to the center of the image
            - save this frame and the bb of the selected vehicle
    - zip up the images, upload to google cloud
    - use PySource python notebook, uploading to google cloud
        - ./Train_YoloV3.ipynb

- What does the classifier output?
    - A tuple containing:
        - (cell_i, cell_j)
        - classification:
            - My car (custom model)
            - GF car (custom model)
            - other car (yolo car)
            - a human
- Determine how to generate ground truth data
    - Handling lighting conditions
    - Labelling data
- Generate ground truth data

## h2
Test 2

### h3
Test 3

#### TODO
text 4

| Name      | Address        | phone number |
| ----      | -------        | ------------ |
| something | something else | a number     |

# Another table, but without the separator
| Name      | Address        | phone number |
| ----      | -------        | ------------ |
| something | something else | a number     |
| something | something else | a number     |

some `code()` goes here

*Bold text*


_italic text goes here_

```
big block of code()
    for( int i=0; i<4; i++ );
```

***
Horiz line 1
***

Horiz line 2
---

* item a
* item b

