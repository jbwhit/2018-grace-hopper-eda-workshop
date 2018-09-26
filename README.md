# 2018-grace-hopper-eda-workshop
Grace Hopper Conference Materials



# Setup

```bash
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