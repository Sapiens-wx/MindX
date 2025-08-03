# MindX
An EEG Game pipeline.
## How to clone this project
1. `git clone git@github.com:Sapiens-wx/MindX.git` to clone this repository
2. Since this repository has two submodules: a Unity project and a python project for recording EEG data and training models, use `git submodule update --init` to update all submodules to its newest version.
3. If you have cloned this repository __and__ the submodules (which means the above two steps are completed), and want to get the newest version of the two submodules, use `git submodule update --remote --merge`.
## Usage
1. __BulletHell__: this is a unity project containing the source code of three custom-developed games specifically designed for EEG game control experiments.
2. __EEG_CNN__: this is a pipeline helping researchers from collecting EEG data using Muse lsl, preprocessing EEG, classifying EEG, predicting EEG in real time, to streaming the realtime EEG prediction into our custom-developed games.
3. __Builds__: this folder contains the executable file (in windows) of the three custom developed games.

A detailed instruction is written in each submodule's `README.md` file.