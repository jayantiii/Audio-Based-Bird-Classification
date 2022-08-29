# Audio Based Bird Classification

This project is being carried out to build a CNN model to classify birds  based on their audio sounds. We have chosen 6 birds for this purpose and the audio dataset is extracted with the means of webscraping.

The project code is divided into 4 files each made for a separate task. 

## Birds Scraping
In this file we make use of selenium library to scrap data from a website (https://indianbirdsong.org/) dedicated towards audio sounds of birds from the Indian region.

## Prepare Data

The preprocessing/preparation of data involves mainly taking each audio and converting it into a mel-spectrogram of 5 second each which will result into one single audio clip giving us many spectrogram images. Hence audio dataset is converted into spectrogram image based dataset.

## Split Data

The dataset is spilt in 8:1:1 ratio for train , validation and test data.

## Final Model

Convolutional neural network model is built upon the architecture of EfficientnetB7 model.
In the end, we achieve training accuracy to be up to  81% and validation accuracy to be up to 73% and testing accuracy of 81%.

The model has consistently increasing accuracy and consistently decreasing loss which signifies a good model.




## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

