## Python packages

- numpy
- opencv-python
- tensorflow
- keras
- requests
- progressbar
- cvlib

Install the required packages by executing the following command.

`$ pip install -r requirements.txt`

**Note: Python 2.x is not supported**

Make sure `pip` is linked to Python 3.x (`pip -V` will display this info).

If `pip` is linked to Python 2.7. Use `pip3` instead.
`pip3` can be installed using the command `sudo apt-get install python3-pip`

Using **Python virtual environment** is highly recommended.

## Usage

### image input

`$ python detect_gender.py -i <input_image>`

### webcam

`$ python detect_gender_webcam.py`
