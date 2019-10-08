# Brain Haemorrhage
![haemorrage](https://user-images.githubusercontent.com/48018142/66402477-8abd3280-ea02-11e9-9655-3fec8d00e46e.png)

# Types of Brain Haemorrhage

![epidural](https://user-images.githubusercontent.com/48018142/66402479-8b55c900-ea02-11e9-8e23-19c9544296ac.png)
![intraparenchymal](https://user-images.githubusercontent.com/48018142/66402480-8b55c900-ea02-11e9-91ed-c10e794a468d.png)
![intraventricular](https://user-images.githubusercontent.com/48018142/66402481-8b55c900-ea02-11e9-99cd-d2cceb4ea59d.png)
![subarachnoid](https://user-images.githubusercontent.com/48018142/66402482-8bee5f80-ea02-11e9-8950-260b745b6d7c.png)
![subdural](https://user-images.githubusercontent.com/48018142/66402486-8d1f8c80-ea02-11e9-8390-14eee617c6ec.png)

# Preprocessing
Our eye can only detect ~6% change in greyscale (16 shades of grey).
<br>
Given 2000 HU of one image (-1000 to 1000), this means that 1 greyscale covers 8 HUs.
<br>
The example of a hemorrhage in the brain shows relevant HUs in the range of 8-70. We won't be able to see important changes in the intensity to detect the hemorrhage.
<br>
This is the reason why we have to focus 256 shades of grey into a small range/window of HU units. (WINDOW)
![HU](https://user-images.githubusercontent.com/48018142/66403731-b5a88600-ea04-11e9-9f68-e8140dbcb9c6.png)
