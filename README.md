# ImageColorizer

This project uses a deep learning model to colorize black and white images. The model and methodology are based on the work by Richard Zhang et al., as well as the OpenCV sample code for colorization.

## Requirements

- Python 3.x
- OpenCV 4.x
- NumPy

## Model Files

Download the following model files and place them in the `model` directory:
1. [colorization_deploy_v2.prototxt](https://github.com/richzhang/colorization/tree/caffe/colorization/models)
2. [pts_in_hull.npy](https://github.com/richzhang/colorization/blob/caffe/colorization/resources/pts_in_hull.npy)
3. [colorization_release_v2.caffemodel](https://www.dropbox.com/s/dx0qvhhp5hbcx7z/colorization_release_v2.caffemodel?dl=1)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ImageColorizer.git
   cd ImageColorizer
   ```

2. Install the required packages:
   ```bash
   pip install numpy opencv-python
   ```

3. Ensure the model files are downloaded and placed in the `model` directory as described above.

## Usage

To colorize a black and white image, use the following command:
```bash
python colorize.py -i path/to/your/image.jpg
```

Replace `path/to/your/image.jpg` with the path to your black and white image.

## Credits

- [OpenCV DNN Colorization Sample](https://github.com/opencv/opencv/blob/master/samples/dnn/colorization.py)
- [Richard Zhang's Colorization Work](http://richzhang.github.io/colorization/)
- [Richard Zhang's Colorization GitHub](https://github.com/richzhang/colorization/)
