<h2>Object Detection Hosted on Streamlit</h2>

<p> The repo contains 2 files: <br> 1. The trained model path that is trained on the <b>Common Objects in Context dataset(COCO)</b> <br> 2. The script for running the model on your browser for any test image </p>
<br>
<h3> Steps to run the code script for running the model locally:</h3>

<h5> Clone the repository locally</h5>

```bash
git clone "https://github.com/anurag2506/simple_detection"
```

<h5> Change the path to the local directory</h5>

```bash
cd simple_detection
```

<h5> Install the specific dependencies</h5>

```bash
pip install -r requirements.txt
```

<h5> Run the streamlit locally on your browser</h5>

```bash
streamlit run yolo.py
```
