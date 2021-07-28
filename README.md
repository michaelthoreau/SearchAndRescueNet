# Satellite Imagery for Search And Rescue Dataset - [ArXiv](https://arxiv.org/pdf/2107.12469.pdf)

This is a single class dataset consisting of tiles of satellite imagery labeled with potential 'targets'. Labelers were instructed to draw boxes around anything they suspect may a paraglider wing, missing in a remote area of Nevada. Volunteers were shown examples of similar objects already in the environment for comparison. The missing wing, as it was found after 3 weeks, is shown below.

![anomaly](https://michaeltpublic.s3.amazonaws.com/images/anomaly_small.jpg)


The dataset contains the following:

| Set           | Images      | Annotations |
| -----------   | ----------- | ----------- |
| Train         | 1808        | 3048        |
| Validate      | 490         | 747         |
| Test          | 254         | 411         |
| Total         | 2552        |4206         |

The data is in the [COCO format](https://www.immersivelimit.com/tutorials/create-coco-annotations-from-scratch), and is directly compatible with faster r-cnn as implemented in Facebook's [Detectron2](https://github.com/facebookresearch/detectron2).

## Getting hold of the Data

Download the data here: [sarnet.zip](https://michaeltpublic.s3.amazonaws.com/sarnet.zip)

Or follow these steps

```shell
# download the dataset
wget https://michaeltpublic.s3.amazonaws.com/sarnet.zip

# extract the files
unzip sarnet.zip
```

## Cite this dataset
```
@misc{thoreau2021sarnet,
      title={SaRNet: A Dataset for Deep Learning Assisted Search and Rescue with Satellite Imagery}, 
      author={Michael Thoreau and Frazer Wilson},
      year={2021},
      eprint={2107.12469},
      archivePrefix={arXiv},
      primaryClass={eess.IV}
}
```

## Acknowledgment
The source data was generously provided by Planet Labs, Airbus Defence and Space, and Maxar Technologies.
