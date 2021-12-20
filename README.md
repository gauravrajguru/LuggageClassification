# LuggageClassification
Computer vision project to predict number of wheels of luggage
This logic ensemble pretrained models Inception, ResNet and Densenet to classify images. Two FC layers are added on top of pretrained model output. The transfer learning phase fixed the pretrained model and train only ensembling FCs. To fasten up the training speed, data loaders are created which will have output of pretrained networks. Hence, in training, images are embedded using these models once and used it to finetune the FC. This reduces training time to minutes from hours.
