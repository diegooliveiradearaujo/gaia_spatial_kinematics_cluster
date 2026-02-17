This project involves the study and analysis of stellar data from the European Space Agency (ESA). We use a sample from the Gaia DR1 (Data Release 1) star catalog of ESA, which contains detailed astrometric and photometric data, such as:
- positions in the sky (coordinates)
- apparent brightness
- for some objects, motion across the sky
- other basic astrometric measurements

We will calculate several kinematic metrics, such as signal-to-noise ratio, distance, proper motion, and tangential velocity, to study how stars move across the sky and to identify potential open clusters.

The dataset can be accessed here: https://cdn.gea.esac.esa.int/Gaia/gdr1/gaia_source/csv/GaiaSource_000-000-000.csv.gz

1 – Clone the Repository

First, install Git on your computer: https://git-scm.com/install/

Then, open the Command Prompt and clone the project repository to your preferred location: git clone https://github.com/diegooliveiradearaujo/gaia_spatial_kinematics_cluster.git

2- Set up the environment

Create a virtual environment to keep all project libraries and resources isolated: python -m venv gaia_env

Activate the newly created virtual environment: gaia_env\Scripts\activate

Finally, install the required libraries listed in the requirements.txt file: pip install -r requirements.txt

3 - Pyhton and Jupyter Notebook

For this project, Python 3.10.9 and Jupyter Notebook 6.5.2 were used.

Install Python 3.10.9 through here: https://www.python.org/downloads/release/python-3109/
Then, activate your virtual environment and install Jupyter Notebook 6.5.2: pip install notebook==6.5.2

Note: The jupyter notebook library is not included in requirements.txt because I run it separately using Anaconda Navigator. It is not strictly necessary to have these exact versions, but using them is the safest way to ensure the project runs correctly.

I hope you enjoy this project, which explores the spread of brightness and beauty across the sky and the constellations. Furthermore, these stars are extremely important for us in understanding how new planets and stars form—some of which exist light-years away in our galactic paradise.
