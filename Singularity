Build: docker
From: pytorch/pytorch:latest

%post
   # in-container bind points for shared filesystems
   mkdir -p /extra /rsgrps /xdisk /uaopt /cm/shared /cm/local
   pip install tqdm
   pip install scipy
   pip install sklearn
   pip install pandas
   pip install spacy
   pip install joblib
   python3 -m spacy download en
