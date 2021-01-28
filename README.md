# Engine Sounds
Generating synthetic Engine textures

# User instructions

  >> git clone https://github.com/prashanthtr/engineSynth.git

  >> cd EngineSounds/

  >> conda create -n EngineSounds python=3.8 ipykernel

  >> conda activate EngineSounds

  >> python3 -m pip install -r requirements.txt --src '.'(please run twice - due to numba dependency error)

# Setup and run jupyter notebook

>> pip install jupyter

>> python3 -m ipykernel install --user --name EngineSounds

>> jupyter notebook

>> Select *EngineTextureVisualization-notebook.ipynb* in the browser interface

# Generate files from commandline
(NOT YET UPDATED)
>> python3 generate.py config_file.json <outType>

>> OutType: 0 (*paramManager*), 1 (*SonyGan*) and 2 (*Tfrecords*)