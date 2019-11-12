# Applying-Face-Makeup

This code applies facial makeup on images of celebrities. It fetches images stored in google drive using Google API and does processing on it to give the final output. Following are the steps to replicate it.

1. Setting up environment <br />
a. Make a conda virtual environment first and connect it to the attached jupyter notebook. Follow [this](https://janakiev.com/blog/jupyter-virtual-envs/) link for more help <br />
b. The submitted program uses dlib library. ‘cmake’ is a prerequisite to install dlib <br />
c. Install cmake first: `conda install -c anaconda cmake` <br />
d. Install dlib using: `conda install -c menpo dlib` <br />
e. Then install all the other requirements given in the requirements file attached `pip -r install --upgrade requirements` <br />
f. When the jupyter notebook is opened, connect it to the new environment that was just made <br />

2. Use of Google API <br />
**NOTE:** For security reasons I have removed my credentials.json file. You will have to refer the guide on Google.
a. Follow [this](https://developers.google.com/drive/api/v3/quickstart/python) link for getting started <br />
b. When you click the button, ‘Enable the Drive API’, a new flash window would appear, download the client configuration through that window <br />
c. The credentials.json file downloaded must be in same folder as that of the jupyter notebook <br />
d. The rest should follow <br />

3. Using dlib for Face Recognition
