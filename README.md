# Neural-Networks-NN-Convolutional-Neural-Networks-CNNs-
	1
		Run script q37.sh. It will output CNN lr0.01 m0.0 w0.0 d0.5.json.
		What it does: q37.sh will run python3 dnn cnn.py with learning rate 0.01, no momentum, no weight
	decay, and dropout rate 0.5. The output file stores the training and validation accuracies over 30 training
	epochs.

	2
		Run script q38.sh. It will output CNN lr0.01 m0.9 w0.0 d0.5.json.
		What it does: q38.sh will run python3 dnn cnn.py --alpha 0.9 with learning rate 0.01, momentum
	0.9, no weight decay, and dropout rate 0.5. The output file stores the training and validation accuracies over
	30 training epochs.
		You will see that 2 will lead to faster convergence than 1 (i.e., the training/validation accuracies
	will be higher than 0.94 after 1 epoch). That is, using momentum will lead to more stable updates of the
	parameters.

	3
		Coding: Building a deeper architecture
		The CNN architecture in dnn cnn.py has only one convolutional layer. In this part,
	you are going to construct a two-convolutional-layer CNN (using the modules you have implemented
	in MLP. Please modify the main function in dnn_cnn_2.py. The code in dnn_cnn_2.py is similar to that
	in dnn cnn.py.

	4
		Run script q310.sh. It will output CNN2 lr0.001 m0.9 w0.0 d0.5.json.
		What it does: q310.sh will run python3 dnn cnn 2.py --alpha 0.9 with learning rate 0.01, momentum
	0.9, no weight decay, and dropout rate 0.5. The output file stores the training and validation accuracies
	over 30 training epochs.
		You will see that you can achieve slightly higher validation accuracies than those in 2.