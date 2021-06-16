# NUQSGD: Provably Communication-efficient Data-parallel SGD via Nonuniform Quantization

Code for quantization methods of the paper:

*Ramezani-Kebrya, A., Faghri, F., Markov, I., Aksenov, V., Alistarh, D., & Roy, D. M. (2021). **[NUQSGD: Provably Communication-efficient Data-parallel SGD via Nonuniform Quantization](https://jmlr.org/papers/v22/20-255.html)**. Journal of Machine Learning Research, 22(114), 1-43.*

## Dependencies
We recommend using Anaconda to install the following packages,

* Python 3.7.1
* [PyTorch](http://pytorch.org/) (>=1.1.0)

## Cuda kernel installation

```
cd nuq/cuda/;
python setup.py install
cd ../../
```

## Running experiments in the paper
The commands used to run the experiments can be found in `pjobs/` directory.
These commands are generated using the `grid_run.py` script. Each experiment is 
described using a function in the `grid/nuq.py` file.

## Reference

If you found this code useful, please cite the following paper:

    @article{ramezanikebrya2019nuqsgd,
      author  = {Ali Ramezani-Kebrya and Fartash Faghri and Ilya Markov and Vitalii Aksenov and Dan Alistarh and Daniel M. Roy},
      title   = {{NUQSGD}: Provably Communication-efficient Data-parallel SGD via Nonuniform Quantization},
      journal = {Journal of Machine Learning Research},
      year    = {2021},
      volume  = {22},
      number  = {114},
      pages   = {1-43},
      url     = {http://jmlr.org/papers/v22/20-255.html}
    }

## License

[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
