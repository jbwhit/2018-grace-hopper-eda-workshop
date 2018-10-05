# 2018-grace-hopper-eda-workshop
Grace Hopper Conference Materials

The slides from our workshop can be found [here](https://www.dropbox.com/s/u3ua82ej73keu8q/2018-GHC-EDA-FINAL-POST.pdf?dl=0). 

The notebook with all of the code to reproduce our plots from the talk are in the notebooks directory. 

# Setup

You'll have to have [conda](https://conda.io/docs/user-guide/install/index.html) installed on your computer for this to work.

```bash
git clone https://github.com/jbwhit/2018-grace-hopper-eda-workshop
cd 2018-grace-hopper-eda-workshop
cd setup
conda env create -f environment.yml
source activate eda3
python -m ipykernel install --user --name eda3 --display-name eda3
```


You'll have to install `git-lfs`. If you are on a Mac and have brew installed you can do `brew install git-lfs`. Otherwise, follow the installation instructions for your setup. 

```bash
git clone https://github.com/MuseumofModernArt/collection
cd collection
git lfs fetch
git lfs checkout

cd ..
git clone https://github.com/MuseumofModernArt/exhibitions
cd exhibitions
git lfs fetch
git lfs checkout
```
