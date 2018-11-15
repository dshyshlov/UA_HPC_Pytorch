Bootstrap: docker
From: pytorch/pytorch:latest

%post
   # in-container bind points for shared filesystems
   mkdir -p /extra /rsgrps /xdisk /uaopt /cm/shared /cm/local
   pip3 install tqdm
   pip3 install scipy
   pip3 install sklearn
   pip3 install pandas
   pip3 install spacy
   pip3 install joblib
   python3 -m spacy download en
