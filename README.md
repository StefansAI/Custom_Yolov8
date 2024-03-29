# Custom_Yolov8
Labeling and training of a custom dataset

<br>
<div style="text-align: center;">
  <img src="images/crows_and_squirrel.jpg" />
</div>
<br>
Head over to the <a href="https://roboflow.com/">Roboflow website</a> and sign up for personal use.
<br>
<div style="text-align: center;">
  <img src="images/roboflow.jpg" />
</div>
<br>
Click on "Upload Data" on the left menu.
<br>
<div style="text-align: center;">
  <img src="images/roboflow1.jpg" />
</div>
<br>
Upload all images to be labeled and used for the training.
<br>
<div style="text-align: center;">
  <img src="images/roboflow2.jpg" />
</div>
<br>
Label each image by starting at one corner and drag to the diagonal corner.
<br>
<div style="text-align: center;">
  <img src="images/roboflow3.jpg" />
</div>
<br>
In the appearing dialog type in the name or select one of the listed ones.
<br>
<div style="text-align: center;">
  <img src="images/roboflow4.jpg" />
</div>
<br>
After all images are labeled, assign all of them to the dataset.
<br>
<div style="text-align: center;">
  <img src="images/roboflow5.jpg" />
</div>
<br>
Take a look at the dataset images.
<br>
<div style="text-align: center;">
  <img src="images/roboflow6.jpg" />
</div>
<br>
On the "Generate" page add some augmentations.
<br>
<div style="text-align: center;">
  <img src="images/roboflow7.jpg" />
</div>
<br>
Last check and create the dataset.
<br>
<div style="text-align: center;">
  <img src="images/roboflow8.jpg" />
</div>
<br>
Export Dataset on the next page.
<br>
<div style="text-align: center;">
  <img src="images/roboflow9.jpg" />
</div>
<br>
The opening dialog will provide a code snippet to be copied into a jupyter notebook for accessing the dataset. Hit the copy icon.
<br>
<div style="text-align: center;">
  <img src="images/roboflow10.jpg" />
</div>
<br>
Roboflow provides a colab notebook, that can be used directly. However, there are a number of code cells for additional testing etc. So I deleted those, changed the traing model from "yolov8s.pt" to "yolov8n.pt" and provided a minimalized version here.
<br>
<div style="text-align: center;">
  <img src="images/colab1.jpg" />
</div>
<br>
Look for this code cell and paste the copied code snippet from your dataset here replacing the highlighted ones.
<br>
<div style="text-align: center;">
  <img src="images/colab2.jpg" />
</div>
<br>
Run all and check the results.
<br>
<div style="text-align: center;">
  <img src="images/colab3.jpg" />
</div>
<br>
I added these cells at the end to automatically download the resulting model file "best.pt" to the local Download folder. This model file can now be renamed and copied to the target platform.
<br>
<div style="text-align: center;">
  <img src="images/colab4.jpg" />
</div>
<br>
<br>
<br>
<a href="https://youtube.com/">Youtube video</a>
<br>
