Install Dependencies
```shell
conda create -n pytorch python==3.7
conda activate pytorch
conda install pytorch torchvision torchaudio cudatoolkit=11.1 -c pytorch -c conda-forge
