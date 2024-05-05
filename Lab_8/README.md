# Lab 8A: Examples

Below is an image of me shelling into my Raspberry Pi using GitBash:

![image](image1.png)  


## X applications

### Ico

![image](image2.png)  

### oclock

![image](image3.png)  

### xcalc
![image](image4.png)  

### xclock
![image](image5.png)  

### xeyes
![image](image6.png)  

### xgc
![image](image7.png)  

### xlogo
![image](image8.png)  

### xman
![image](image9.png)  

## Numpy Array

![image](image10.png)  
![image](image11.png)  

## Review and Run Python Code

### pyplot_simple.py
![image](image12.png)  

### simple_plot.py
![image](image13.png)  

### pyplot_formatstr.py
![image](image14.png)  

### ticklabels_demo_rotation.py
![image](image15.png)  

### pyplot_three.py
![image](image16.png)  

### pyplot_two_subplots.py
![image](image17.png)  

### pyplot_scales.py
For this file, I recieved an error, likely due to depreciation. I had to change `linthreshy` to `linthresh` and then it worked.
![image](image18.png)  

### pyplot_annotate.py
![image](image19.png)  

### pyplot_major_minor_demo1.py
![image](image20.png)  

### legend_demo.py
![image](image21.png)  

## Histograms, box plots, regression, and interpolation

### Scatter_demo.py
![image](image22.png)  

### Histogram_demo_features.py
![image](image23.png)  

### pyplot_text.py
![image](image24.png)  

### histogram_demo_extended.py
![image](image25.png)  

### boxplot_demo.py
![image](image26.png)  

### linreg.py
![image](image27.png)  

### interpolation.py
![image](image28.png)  


## Classification, cross-validation (CV), and support-vector machine (SVM)

### plot_lda.py
![image](image29.png)  

### plot_lda_qda.py
Had to correct ellipse arguments here: 
`angle = np.arctan2(u[1], u[0])  # using arctan2 instead of arctan
    angle = np.degrees(angle)  # converting radians to degrees
    ell = mpl.patches.Ellipse(mean, 2 * np.sqrt(v[0]), 2 * np.sqrt(v[1]),
                              angle, color=color, edgecolor='yellow', linewidth=2, zorder=2)`
![image](image30.png)  

### plot_cv_predict.py
![image](image31.png)  

### plot_cv_diabetes.py
![image](image32.png)  

### traffic.py
![image](image33.png)  

## Keras and TensorFlow


### keras_diabetes.py
Here I had to set the envirnment variable `PYTHONENCODING` to this: `PYTHONIOENCODING=utf-8`
![image](image34.png)  

### keras_first_network.py
![image](image35.png)  

## Titanic example

### titanic_1.py
![image](image36.png)  

### titanic_2.py
![image](image37.png)  



