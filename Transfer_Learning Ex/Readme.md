
Applied Transfer Learning On VGG


VGG pretrained model used which uses imagenet database

VGG produces 1000 Classes but we modified that as per our class need i.e 5 Different Classes of flowers

Freeze wts in Conv and Pooling layers (fixed faeture attractor)
Final layer replaced by new Fully Connected Layer
Train ALL the fully connected layers
	- fine tune in 2 linear layer(pretrained)
	-  newly train the last replaced layer

