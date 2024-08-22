
# SketchQL Demonstration

## Description

Sketch-QL is a video database management system for retrieving video moments with a sketch-based query interface.This interface allows users to specify object trajectory events with simple mouse drag-and-drop operations.
Using a pre-trained model that encodes trajectory similarity, Sketch-QL achieves zero-shot video moments retrieval by performing similarity searches over the video to identify clips that are the most similar to the visual query. 

## How to Run

1. git clone https://github.com/tldraw/tldraw-v1.git
2. git clone this repository to get the sketch-ql-backend and core-example-advanced
3. replace the core-example-advanced folder with the folder from here 

### Terminal window 1:

1. cd sketchql-backend

2. Install requirements\
pip install -r requirements.txt

3. Download dataset\
Please download the traffic dataset from https://www.dropbox.com/scl/fi/qormqlzuijb8133um0wa7/VIRAT_S_050300_01_000148_000396.mp4?rlkey=if1vmf14md7nynjuepv9s903j&dl=0 and put it in the data/videos/ folder

4. Download model checkpoint\
Download from https://www.dropbox.com/scl/fi/5jnqj57idzhpm68sjyfb8/model_cp.pt?rlkey=sbz0ix15ofbz0x12d6714v5wu&dl=0 and put it in the data/model_checkpoint folder

5. Run server\
Run the script server.py\
python3 server.py

### Terminal window 2:

1. install yarn\
npm install -g yarn

2. Run code\
cd tldraw-v1\
yarn install\
yarn start:core\
open localhost://5421 in your browser


## Video
A video demonstrating how SketchQL works can be found in the video folder


