## CNN for Human Activity Recognition

<p>
<a href="https://github.com/yang12313/Human-activity-Detection/blob/f115161c1c4f0586073733e20d86672f9fa8ef3c/Activity%20Detection.ipynb">Python notebook</a> for project on device human Activity Recognition. Implementation of a CNN for Human Activity Recognition in Tensorflow 1.15</a>.
</p>
<p>A light weight two layer CNN is applied for this task as the model can be easily deployed to wearable device through TFlite</p>

<p>data is segmented through a fixed size sliding window with 50% overlapping region to capture the time series pattern. A confusion Matrix is applied for the performance verification and is shown below</p>
<p></p>
<img src="Confusion Matrix.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" width="400" height="300" />

### Tools Required

Libraries required to run the code provided in the notebook:
* Tensorflow
* Numpy
* Matplotlib
* Pandas

### Dataset

For verification purposes, only 1/3 of the WISDM Actitracker dataset is used in the repo. The full version of dataset for model training can be downloaded from the following [[link]](http://www.cis.fordham.edu/wisdm/dataset.php)

