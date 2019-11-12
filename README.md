# Applying-Face-Makeup

This code applies facial makeup on images of celebrities. It fetches images stored in google drive using Google API and does processing on it to give the final output.

1. Setting up environment
a. Make a conda virtual environment first and connect it to the attached jupyter notebook. Follow this link for more help
b. The submitted program uses dlib library. ‘cmake’ is a prerequisite to install dlib
c. Install cmake first: `conda install -c anaconda cmake`
d. Install dlib using: `conda install -c menpo dlib`
e. Then install all the other requirements given in the requirements file attached
f. When the jupyter notebook is opened, connect it to the new environment that was just made

2. Use of Google API
a. Follow this link for getting started
b. When you click the button, ‘Enable the Drive API’, a new flash window would appear, download the client configuration through that window.
c. The credentials.json file downloaded must be in same folder as that of the jupyter notebook



