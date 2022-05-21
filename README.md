# Video-to-ASCII

This project was intended to convert a picture/image or video to its ASCII version. Many such approaches have been implemented. For example, you can choosen on letter and display the image using this letter in many collors or we can use a black-and-white version with all ASCII characters. At last, there is a mix where we use all ASCII characters (which give a good sharpness) with colors, which yields very nice images. The use of ASCII only in black-and-white is nice when you have black backgrounds. There is also one version where we display the image using a sample text.

## Examples

Let me show here some sample outputs for an image. 

Original picture:

![comida-mexicana-00](https://user-images.githubusercontent.com/77543666/169663030-d1aeaa4e-3eeb-423f-8eb5-3236ec0c3c86.png)

Picture with colors using "=":

![out-=](https://user-images.githubusercontent.com/77543666/169663034-68a14b8f-8c94-4824-9ed6-c80761be00c8.png)

Picture with colors using "H":

![out](https://user-images.githubusercontent.com/77543666/169663036-23f66a34-48a7-4ad5-a881-a0f15874f5fa.png)

Picture with colors using a text:

![out-text](https://user-images.githubusercontent.com/77543666/169663035-cfc61c89-6352-4088-ad8e-daf118df5057.png)

Picture with colors using luminosity-chosen ASCII characters:

![out_grey](https://user-images.githubusercontent.com/77543666/169663037-32ab53d7-0eba-43d3-a660-3246b51e104a.png)


Unfortunately, the videos are too large to include a sample here, but you can easily apply it to any given video on your computer! 

## How to Use

Put your video file in the data/ folder. Then. in the file `videos.py`, write the name of your video and the desired name of the output. You can choose the different render function to play with the various images encondings, but the default configured is converting to a given letter in color. After that, just run! 

