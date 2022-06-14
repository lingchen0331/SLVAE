# SL-VAE

The code has been tested under Pytorch 1.8

To test the code, simply run the following command  
```
cd <main>
python slvae.py -d <datasetname>
```
Datasets names are 'jazz_SIR', 'jazz_SI', 'cora_ml_SIR', 'cora_ml_SI', 'power_grid_SIR', 'power_grid_SI', 'karate_SIR', 'karate_SI', 'netscience_SIR', 'netscience_SI'
Run the following code to see available parameters that can be passed in:  
```
python slvae.py -h
```

If you find this work useful for your research, please cite
```
@inproceedings{ling2022source,
  title={Source Localization of Graph Diffusion via Variational Autoencoders for Graph Inverse Problems},
  author={Ling, Chen and Jiang, Junji and Wang, Junxiang and Zhao, Liang},
  booktitle={Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery \& Data Mining},
  year={2022}
}
```
