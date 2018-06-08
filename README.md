# FeatureNet Database

We developed a novel framework using Deep 3D Convolutional Neural Networks (3D-CNNs) termed **FeatureNet** to learn machining features from CAD models of mechanical parts. FeatureNet learns the distribution of complex machining feature shapes across a large 3D model data set and discovers distinguishing features that help in recognition process automatically. To train FeatureNet, a large-scale mechanical part datasets of 3D CAD models with labeled machining features is synthetically constructed. For more details, please refer to our <a href="https://doi.org/10.1016/j.cad.2018.03.006">paper</a> published in Computer-Aided Design journal, Vol. 101, 2018. The FeatureNet database is provided in this repository.

This repository includes a zipped folder consisting of the complete FeatureNet database. The zipped folder consists of 24 sub-folders, each representing a unique machining feature with class label (from 0-23). Every sub-folder has 1000 .STL files, which are randomly generated samples of the corresponding machining feature. The list of machining features and their parameters are provided in the [.PDF file](FeatureList.pdf) included with the repository.

If you use our dataset for your work, please cite:
> Zhang, Z., Jaiswal, P., & Rai, R. (2018). FeatureNet: Machining feature recognition based on 3D Convolution Neural Network. Computer-Aided Design, 101, 12-22.

*****************************************************************
### Owner:
	MAD Lab
	Department of Mechanical and Aerospace Engineering
	University at Buffalo, Buffalo, NY - 14260
	http://madlab.eng.buffalo.edu/
*****************************************************************