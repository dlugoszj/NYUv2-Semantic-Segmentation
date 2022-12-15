# RGB-D Semantic Segmentation with UNet and ENet

## Authors

[@fvolcic](www.github.com/fvolcic)

[@dlugoszj](www.github.com/dlugosz)

## Project Background
The goal of the project was to figure out the difference in the accuracy of semantic segmentation when using RGB data and RGB-D data. We used an implementation of ENet and UNet to test the differences. We trained the networks based on a combination of Dice Loss and Cross Entropy Loss. From here we calculated the accuracy of the networks by using the mean IoU (Intersection over Union) and mean pixel accuracy. 

The reference paper for this repository is linked [here]().

## Installation

To setup the environment, run 
 
```bash
pip3 install -r requirements.txt
```
## Usage

Once installed, you can train the networks using any of the train files. You can visualize the results with the associated ipynb files. 

## License

[MIT](https://choosealicense.com/licenses/mit/)