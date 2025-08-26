# SketchQL Demonstration

SketchQL is a video database management system for retrieving video moments with a sketch-based query interface.This interface allows users to specify object trajectory events with simple mouse drag-and-drop operations. Using a pre-trained model that encodes trajectory similarity, SketchQL achieves zero-shot video moments retrieval by performing similarity searches over the video to identify clips that are the most similar to the visual query.

## 🚀 How to Run

### Terminal Window 1: Backend Server

1. First, set up the backend following the [SketchQL installation guide](https://github.com/georgia-tech-db/SketchQL?tab=readme-ov-file#%EF%B8%8F-installation).

2. Start the backend server
```bash
# Navigate to SketchQL/
python3 server.py
```

### Terminal Window 2: Frontend Application
1. Clone the `tldraw` repository. Please clone v1 (original version) instead of the new tldraw.
```bash
git clone https://github.com/tldraw/tldraw-v1.git
```

2. Replace the `tldraw-v1/examples/core-example-advanced` folder with the `core-example-advanced` folder from this repository

3. Install dependencies 

```bash
# Install yarn if not already installed
npm install -g yarn

# Navigate to project and install dependencies
cd tldraw-v1
yarn install
```

4. Start development server
```bash
yarn start:core
```

5. Open your browser and navigate to: `http://localhost:5421`


## 🎥 Demonstration Video
A video demonstrating how SketchQL works can be found under the `video/` folder


## 🔗 Related Resources
- Backend Repository: [Georgia Tech DB SketchQL](https://github.com/georgia-tech-db/SketchQL)
- tldraw Framework: [tldraw-v1 GitHub](https://github.com/tldraw/tldraw-v1)
