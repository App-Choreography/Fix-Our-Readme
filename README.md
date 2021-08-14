# Fix-Our-Readme!

### Get an invite to our organisation when you contribute!

## Firstly, make a pull request with your fixes, and then create an issue, either using our templates, or free style!

## See how to contribute: 
[How-To-Contribute](https://github.com/App-Choreography/How-To-Contribute)

## Here is the list on what to fix:

## > Please only choose 1 error per coder, so everyone has a go!

- [x] Headings on where they are designed:

`#` This is where a H1 is meant to be!

- [x] Capital letters where they are missing, at the start of every sentence.
- [x] Spelling mistakes.
- [x] Broken markdown: 

`##This is a H2` ----> `## This is a H2`

------------------------------------------

## Are you ready...
Here we go!

## How to make a website with mutiple backgrounds:

###here is the screenshot of the website we will master today!

![alt text](![image](https://user-images.githubusercontent.com/70807500/129236192-d50c8137-4cae-4b0f-b489-6b2bdf4458ad.png)

Luks cool right?

## The reqired code you will need:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Under sea demo</title>
    <link rel="stylesheet" type="text/css" href="index.css">
</head>

<body>
    <div class="bg-image img1"></div>
    <div class="bg-image img2"></div>
    <div class="bg-image img3"></div>
    <div class="bg-image img4"></div>
    <div class="bg-image img5"></div>
    <div class="bg-image img6"></div>
    <div class="bg-text">WORD BLA BLA BLA</div>
</body>

</html>
```

###The HTML:

as allways, their will always be a boilerplate::;

```html
<!DOCTYPE html>
<html lang="en">
  <head>
  </head>
  <body>
  </body>
</html>
```

the `body` tagg shoows the elements of the DOM(Document Object Moddell).

## Lets carrie on!

```html
    <div class="bg-image img1"></div>
    <div class="bg-image img2"></div>
    <div class="bg-image img3"></div>
    <div class="bg-image img4"></div>
    <div class="bg-image img5"></div>
    <div class="bg-image img6"></div>
    <div class="bg-text">WORD BLA BLA BLA</div>
```

##So we have 6 `<div>` elements, that contain imgs, and our last div contains our main twxt!

## Time for the CSS!

```css
body, html {
    height: 100%;
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
}

* {
    box-sizing: border-box;
}

.bg-image {
    height: 50%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.img1 {background-image: url("https://wallpaperaccess.com/full/1321265.jpg");}
.img2 {background-image: url("https://www.irishnews.com/picturesarchive/irishnews/irishnews/2018/03/11/181039187-d87ff77c-48c4-4a04-89d0-feae54f2faec.jpg");}
.img3 {background-image: url("https://i.natgeofe.com/n/705ec8f5-2a1b-43c1-98ba-1d8ebfe58fce/01-trumps-ocean-policy-nationalgeographic_2461163_16x9.jpg?w=636&h=358");}
.img4 {background-image: url("https://ml8ygptwlcsq.i.optimole.com/fMKjlhs-Dn1kuuR_/w:412/h:274/q:auto/https://www.unite.ai/wp-content/uploads/2020/04/fish-288988_960_720.jpg");}
.img5 {background-image: url("https://ensia.com/wp-content/uploads/2017/02/feature_ocean_soundscapes_main2-1-760x378.jpg");}
.img6 {background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQg069NjXxl1pnbY0J6a7JOkoqAGMp3Kh2YcIfim4M_KX84wvX_sF4e7UFbVnhRg-OWOUU&usqp=CAU");}

.bg-text {
    background-color: rgb(0, 0, 0);
    background-color: rgba(0,0,0, 0.4);
    color: white;
    font-weight: bold;
    font-size: 80px;
    border: 10px solid #f1f1f1;
    position: fixed;
    top: 50%;
    left:50%;
    transform: translate(-50%, -50%);
    z-index: 2;
    width: 300px;
    padding: 20px;
    text-align: center;
}
```





















🏗 Still In Progress, will be back VERY soon! 🏗

