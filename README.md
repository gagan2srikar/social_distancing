# Social-distance-detection


#### Github usually doesn't support files larger than 25 Mb.You can find the yolo weights in [My google drive](https://drive.google.com/file/d/1QrGGrZl-K2z9IH410o9oeGvbKdIDjGIS/view?usp=sharing) 
* Download it & move to yolo-coco folder

# For CPU:

## To run this code in your terminal:
* ***Open your terminal**
* ***Change directory to where you have downloaded this code***
* ***Install python3 if you have not, if installed already then it's ok!***
* **Run**  `  python3 -m venv venv  ` ***to create a virtual environment named venv.***
* **Run**   `  source venv/bin/activate  ` 
***to activate your environment!***
* **Write**   `  pip install -r requirements.txt  ` 
***to install the python dependencies related to this project like opencv,numpy,scipy etc.***
* **Run the command** `time python social_distance_detector.py --input pedestrians.mp4 --output output.avi --display 1
` ***to run your social distance detection project***


video capture before:

https://github.com/gagan2srikar/social_distancing/assets/112459680/7e1736d3-b513-4572-8109-ca3891754a3f



video capture after:

![my_output1](https://github.com/gagan2srikar/social_distancing/assets/112459680/add37373-124b-43de-9891-4e4ded12bfb4)



