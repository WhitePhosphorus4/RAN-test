# RAN-test
RAN baseline test project





## Environment

### Require

- 



The required environment could be install with the following code

```bash
# cuda 11.1

# torch 1.8.0
conda install pytorch==1.8.0 torchvision==0.9.0 torchaudio==0.8.0 cudatoolkit=11.1 -c pytorch -c conda-forge

# pyG
pip install torch_scatter -f https://pytorch-geometric.com/whl/torch-1.8.0%2Bcu111.html
pip install torch_sparse -f https://pytorch-geometric.com/whl/torch-1.8.0%2Bcu111.html
pip install torch_cluster -f https://pytorch-geometric.com/whl/torch-1.8.0%2Bcu111.html
pip install torch_spline-conv -f https://pytorch-geometric.com/whl/torch-1.8.0%2Bcu111.html
pip install torch-geometric

# ogb
pip install ogb
```

