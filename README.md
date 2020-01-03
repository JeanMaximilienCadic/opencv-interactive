# opencv-interactive
![alt text](https://raw.githubusercontent.com/JeanMaximilienCadic/opencv-interactive/master/imgs/opencv-annotate.png)

A simple tool to annotate image files online.

### Prerequisites

To start install opencv in a conda environment.
```
conda install -c conda-forge opencv
conda install -c ninedw gnutools-python
```

### How to
You should change the filtering system in the main (l68) to load the desired files to annotate
```
...
files = listfiles('data', ['.jpg'])
...
```

Then run
```
python main.py
```

Use the mouse to draw roi on the image and press enter to move the next image.

The results will be written into a `annotations.txt` file.

## Authors

* **CADIC Jean Maximilien**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
