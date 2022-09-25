# Final Project

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#dependencies">Dependencies</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#authors">Authors</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Our goal is to classify traffic signs using a convolutional neural network (CNN). The training data set has a total of 10 traffic signs (10 classes). 

![encodings](https://user-images.githubusercontent.com/62025141/180517436-1753bcd3-3ea0-410e-b2c2-e7a9afa9d253.PNG)


Training data and labels:
* ["data_train.npy"](https://ufl.instructure.com/files/69641951/download?download_frd=1)
* ["labels_train.npy"](https://ufl.instructure.com/files/69639892/download?download_frd=1)

<!-- GETTING STARTED -->
## Getting Started


### Dependencies

* Pytorch 1.9.0
  ```sh
  conda install pytorch
  ```
* NumPy 1.20.1
  ```sh
  conda install numpy
  ```
* tqdm 4.53.0
  ```sh
  conda install tqdm
  ```
* matplotlib 3.4.1
  ```sh
  conda install matplotlib
  ```
* sklearn 0.24.1
  ```sh
  conda install sklearn
  ```

<!-- USAGE EXAMPLES -->
## Usage

1. Training the model
	* A. The **train.ipynb** notebook is split into two sections: 'model class and
	functions' and 'main.' 
	* B. At the beginning of the 'main' section, edit the data and label paths to
	lead to the training data and training labels, respectively.
	* C. Run all the cells.
	* D. The accuracies and losses of the training and validation sets across epochs
	will be plotted.
	* E. The last cell saves the trained model.

2. Testing
	* A. The **test.ipynb** notebook is split into two sections: 'model class and
	functions' and 'main.' 
	* B. At the beginning of the 'main' section, edit the data and label paths to
	lead to the test data and test labels, respectively. 
	* C. Run all the cells (the model saved from training will be loaded).
	* D. The last cell will print the accuracy and the confusion matrix.

3. Testing extra credit
	* A. Same as testing, except using **test_ec.ipynb**.


<!-- Authors -->
## Authors

* Bradley Johnson   - bradley.johnson@ufl.edu
* Anna Hampton      - anna.hampton@ufl.edu
* Ipshita Aggarwal  - ipshita.aggarwal@ufl.edu
* Moisses Rodriguez - rodriguezmoisess@ufl.edu
