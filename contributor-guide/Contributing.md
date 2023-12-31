# 🛠️ Contributing

A contributing guide for MemeWiki.

 This guide will teach you how to
contribute articles for MemeWiki.

# 🟩 How do I contribute to MemeWiki?
## 📃 First of all, to contribute there are some requirements:
> 💻 Knowledge on HTML, CSS (javascript not necessary)

> 🖱️ Have a basic understanding on Photopea

> 🧑‍💻 Must know the basics of VSCode and Git

> ✏️ Good article writing skills :D

✅ If you passed these requirements, dm me on Discord. My username is **alluxd**.
<br>

<hr>
<br>

## 🖋️ Making banners with Photopea
<details>
<summary> 
 Click to expand

 </summary>


### An example of a banner, this uses the Lemonmilk font.
![Alt text](./resources/tempbanner.png "example banner")
### 1. Visit photopea.com
### 2. Click on the 'New Project' button
### 3. Set the resolution to 1280x720
### 4. Add an image of the character/meme you're making an article on
<details>
  <summary> 4.1: To remove the background of a meme: </summary>
<hr>

#### 1. Select your meme's layer

#### 2. Use the magic wand tool:

#### 3. Click on select subject

#### 4. Hit Ctrl + J (Command + J on MacOS)

#### 5. There should be two layers now, remove the one with the background by
selecting the layer and hit 'Delete' on your keyboard.

### This step is optional, don't worry if it doesn't work.
<hr>

</details>



### 5. Double click the meme layer and go to stroke. Change it as you wish. (DONT MAKE IT UGLY)
### 6. Move it to the left or center.
### 7. Add text, make sure you use either of these fonts: Lemonmilk or Poppins
<details>
<summary> 7.1: Adding a font </summary>
<hr>

### 1. For Lemonmilk

#### Go to this link: https://www.dafont.com/lemon-milk.font
#### 2. Download the font, it should download as a .zip file.
#### 3. Extract the file into a folder (It can be named whatever you want)

<hr>

### 2. For Poppins

#### 1. Go to this link: https://fonts.google.com/specimen/Poppins (You may have to sign in)
#### 2. Download the font, it should also be a .zip file.
#### 3. Extract the zip file into a folder.

<hr>

### 3. Adding the font to Photopea

#### 1. Use the text tool
#### 2. Click on the fonts tab. (It should say "DejaVu Sans")
#### 3. Click on 'Load Font'
#### 4. A file explorer window should open. Find the folder where you extracted the font files in
#### 5. Select all the .ttf/.otf files and click Enter
#### 6. Wait  a bit, and then search the name of the font you added.
</details>
<hr>

### 8. Add effects, change colors and make the text look good!

### 9. Once you're done, click on File>Export As>PNG (name it {memename}Banner, eg: scatBanner), and save it to the images folder in the website directory

</details>

<br>

## 🧑‍💻 Forking and running the repository
<details>
<summary> 
Click to expand
</summary>

#### 1. Open a folder in vscode.
#### 2. Click on "Terminal" in the top bar, and then "New Terminal"
#### 3. Type ``git clone https://github.com/alluxd/memewiki.git <folder name>`` (Replace "folder name" with the name of the directory). Then hit enter.
#### 4. Open the index.html in editing mode
#### 5. Make sure you have LiveServer installed in VSCode extensions.
#### 6. Click on "Go Live", it should open in a chrome window

</details>

<br>

## 🖱️ Making/Editing Articles
<details>
<summary> 
Click to expand
</summary>

#### 1. Copy the contents of the *tempCSS.css* file. 
#### 2. Open the pages folder, and create two files.
> articlename.html

> articlename.css (in styles folder)

#### 3. Replace "articlename" with the name of the meme. It can be shortened, like: smurf cat would be scat.

#### 4. Copy the contents of the tempHTML.html file and paste it in your html file. Do the same with the CSS. 

#### 5. Tweak and modify it as much as you want. Make sure it matches the theme like all the other pages.


### There are some more helping info in both the tempCSS and tempHTML files. 
### If you have any other questions, you can dm me.
</details>



## ➕ Pushing to the repository
<details>
<summary> 
Click to expand
</summary>

### Note: If you are adding the article, please inform me so that I can show it in the articles page.

#### 1. Open a new terminal.
#### 2. ``git init``
#### 3. ``git remote add origin https://github.com/alluxd/memewiki.git``
#### 4. ``git pull origin main``
#### 5. ``git add .``
#### 6. ``git commit -m 'Commit message here'``
#### 7. ``git push origin main``
#### 8. That's all!



</details>

## ❔ FAQ
### 1. How do I use the images folder?
> You can put 2 types of images in the folder: Article banner (photopea) and The Meme's image. Name the banner you made from photopea like: '(memenamehere)Banner'. For the meme's image, you can download it from google and put it inside the images folder. Name it your meme's name.

> To access the image on an html file, use ``<img src='./images/imagenamehere.png/jpg>``, sometimes you may need to extend the path by adding a '../'

### 2. Can I modify the index.html file?
> No, unless you have the permission to do so.



## 🎤 Additional Stuff
### I'm sorry if you didn't understand how to do something in this tutorial. I tried to make it as understandable as possible. If you still have more doubts don't refrain from adding me on Discord. 