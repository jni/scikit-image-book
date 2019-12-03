# Preparation

## Format

The tutorial consists of lecture segments, followed by hands-on
exercises.  We strongly encourage you to bring a laptop with all the
required packages installed in order to participate fully.

## Software required

- Python

  If you are new to Python, please install the
  [Anaconda distribution](https://www.anaconda.com/distribution/) for
  **Python version 3** (available on OSX, Linux, and Windows).
  Everyone else, feel free to use your favorite distribution, but
  please ensure the requirements below are met:

  - `numpy` >= 1.12
  - `scipy` >= 1.0
  - `matplotlib` >= 2.1
  - `scikit-image` >= 0.16
  - `scikit-learn` >= 0.18
  - `napari` >= 0.2.6

  Please see "Test your setup" below.

- Jupyter

  The lecture material includes Jupyter notebooks.  Please follow the
  [Jupyter installation instructions](http://jupyter.readthedocs.io/en/latest/install.html),
  and ensure you have version 4 or later:

  ```bash
  $ jupyter --version
  4.4.0
  ```

## Download lecture material

1. [Install Git](https://git-scm.com/downloads)
2. Clone the repository at
   [https://github.com/jni/skimage-tutorials](https://github.com/jni/skimage-tutorials)
3. Switch to the `monash-df2` branch: git checkout --track origin/monash-df2

We may make editorial corrections to the material until the day before
the workshop, so please execute `git pull` to update before class.

## Test your setup

Please switch into the repository you downloaded in the previous step,
and run `check_setup.py` to validate your installation.

On my computer, I see (but your version numbers may differ):

```
[✓] scikit-image  0.16.2
[✓] numpy         1.17.0
[✓] scipy         1.3.1
[✓] matplotlib    3.1.1
[✓] notebook      6.0.1
[✓] scikit-learn  0.21.1
[✓] napari        0.2.6
```

**If you do not have a working setup, please contact the instructors.**
