# Neural Style Transfer

Neural Style Transfer using OpenCV.

## Installation

1. Install Python3 and pip.
2. Install virtualenv (pip install virtualenv).
3. Create virtualenv (virtualenv venv) and activate (source venv/bin/activate).
4. pip install -r requirements.txt.
5. cd models && chmod +x download.sh && ./download.sh (This step is required to run only once)
6. After the download completes, just ensure that the folder structure for models is
   similar to the following (move the folders here and there if not):&nbsp;&nbsp;<br> > models<br> &nbsp;&nbsp;&nbsp;> eccv16<br> &nbsp;&nbsp;&nbsp;> instance_norm<br> &nbsp;&nbsp;&nbsp;> download.sh<br>
7. i. (for webcam live video) python init.py <br>&nbsp;&nbsp;&nbsp; > Press 'n' to choose next style, 'p' to go to the previous style, and 'q' to quit.<br>ii. (for styling image) python init.py -i </path/to/image/> -md </path/to/actual/model(inside eccv16 or instance_norm.) <br>&nbsp;&nbsp;&nbsp; > Eg. python init.py -i /home/sample.png -md ./models/instance_norm/mosaic.t7
