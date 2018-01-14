# SCSG

Code for the paper [Non-Convex Finite-Sum Optimization Via SCSG Methods](https://papers.nips.cc/paper/6829-non-convex-finite-sum-optimization-via-scsg-methods.pdf) by Lihua Lei, Cheng Ju, Jianbo Chen, Michael I. Jordan. 

## Dependencies
This project runs with Python 2.7. Please `pip install` the following packages:
- `numpy`
- `tensorflow`

Currently it requires Tensorflow of version 1.2.1 or higher. 

## Running in macOS or Ubuntu
We provide the source code to run the MNIST example. Run the following commands in shell:

```shell
git clone https://github.com/Jianbo-Lab/SCSG
cd SCSG  
python run_mnist.py
```

You can find the results in `experiments/results`.


## Citation
If you use this code for your research, please cite our [paper](https://papers.nips.cc/paper/6829-non-convex-finite-sum-optimization-via-scsg-methods.pdf):
```
@inproceedings{lei2017non,
  title={Non-convex finite-sum optimization via scsg methods},
  author={Lei, Lihua and Ju, Cheng and Chen, Jianbo and Jordan, Michael I},
  booktitle={Advances in Neural Information Processing Systems},
  pages={2345--2355},
  year={2017}
}
```