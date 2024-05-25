MacOS Conda packages:
conda install pytorch::pytorch torchvision torchaudio -c pytorch
conda install -c conda-forge spacy (https://spacy.io/usage)
conda install pandas
conda install -c anaconda gensim
conda install anaconda::nltk
conda install anaconda::transformers

MacOS pip packages:
pip install torch_geometric (conda package is not available for m1)
python -m spacy download en_core_web_sm (https://spacy.io/usage)
python -m spacy download en_core_web_lg

Windows Conda packages:
conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia (something wrong, cuda is not working)
conda install pyg -c pyg (something wrong, cuda is not working)

conda install -c conda-forge spacy
conda install -c conda-forge cupy
conda install pandas
conda install anaconda::nltk
conda install anaconda::transformers

Windows pip packages:
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
pip install torch_geometric pyg_lib torch_scatter torch_sparse torch_cluster torch_spline_conv -f https://data.pyg.org/whl/torch-2.3.0+cu121.html
pip install scikit-learn
pip install pyresparser

python -m spacy download en_core_web_sm (https://spacy.io/usage)
python -m spacy download en_core_web_lg
