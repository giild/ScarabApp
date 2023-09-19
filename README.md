# pocketai: 

![pocketai Icon](https://github.com/giild/pocketaiApp/blob/main/images/pocketai_256.png)
![pocketai lite Icon](https://github.com/giild/pocketaiApp/blob/main/images/pocketai-lite_256.png)

Issue tracking and documentation for pocketai and pocketai lite.

## About pocketai
pocketai is a visualization and debugging tool for machine learning models. 

## About pocketai lite
lite is a free MacOS app for machine learning development. It provides a subset of features in pocketai. The lite version doesn't have the debugging or model visualization features. To signup for pocketai beta program, please visit the link below.

## Feature Table

| Feature                           | pocketai | lite |
|-----------------------------------|----------|------|
| accuracy & loss chart             | X        | X    |
| test dataset results              | X        | X    |
| search and filter test results    | X        | X    |
| record prediction for all epochs  | X        | X    |
| heatmap of model weights          | X        |      |
| heatmap of diff between epochs    | X        |      |
| heatmap of runtime profile        | X        |      |
| heatmap of diff between profiles  | X        |      |


### Heatmap

![Diff between checkpoint Heatmap](./screenshot/diff_heatmap.png)

Visualize the parameter changes between checkpoint models. When the model overfits to the training dataset, visualizing the parameter changes between epochs can help identify which weights contribute to regression.

### Profile and debug bad predictions

![Layer Activation Output](./screenshot/profile_activation_heatmap.png)

Visualize the layer activations with heatmaps to get a better understanding why predictions are wrong.

### View Test Dataset errors

![Test Dataset errors](./screenshot/epoch_test_img_report.png)

Quickly view the prediction accuracy for the test dataset.

### Accuracy & Loss Chart

![Training accuracy and Loss](./screenshot/hdf5_model_list.png)

Accuracy and loss chart for the training session.

## Where to get pocketai
During the beta testing period, you can signup for the beta program https://www.giild.com/

## Issue Guidelines
We value feedback and want to hear you. Please review the issues guidelines before submitting a new issue. This helps us manage and prioritize the issues. It also helps users search the issues and get the information quickly.

### Etiquette

We value honest feedback and it's critical for the long term health of the application. 

1. avoid name calling and shouting with all caps
2. avoid profanity or NSFW
3. avoid hijacking other people's issue tickets

### Bugs

1. Include system and build information
2. Include any errors or relevant logs
3. If you can provide a repeatable test case, please attach it to the issue or provide a link to download the material
4. Include a description of the steps to reproduce the bug

### Feature Request

1. Provide a detailed description of the feature
2. Explain why you feel it would be useful
3. Include any screencaps or mockups that might help us prioritize the feature

### General Feedback

1. Anything that isn't a bug or feature request is considered general feedback
2. Questions about documentation
3. Questions about product roadmap
   
