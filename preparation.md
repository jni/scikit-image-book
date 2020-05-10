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

  - scikit-image >= 0.17
  - numpy >= 1.12
  - scipy >= 1.0
  - matplotlib >= 2.1
  - notebook >= 4.0
  - scikit-learn >= 0.18
  - pandas >= 0.25
  - napari >= 0.3

  Please see "Test your setup" below.

- Jupyter

  The lecture material includes Jupyter notebooks.  Please follow the
  [Jupyter installation instructions](http://jupyter.readthedocs.io/en/latest/install.html),
  and ensure you have version 4 or later and notebook version 6 or later:

  ```bash
  $ jupyter --version
  jupyter core     : 4.6.3
  jupyter-notebook : 6.0.3
  ...
  ```

## Download lecture material


### Option 1: using git

If you are familiar with git, you can clone the repository at
https://github.com/jni/skimage-tutorials. You need a specific branch,
so use the command:

```
git clone --depth 1 --single-branch --branch monash-df2020-05 https://github.com/jni/skimage-tutorials
```

We may make editorial corrections to the material until the day before
the workshop, so please execute `git pull` to update before class.

### Option 2: download a zip file



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
