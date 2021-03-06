
# Photo Gallery

Here’s an example of how this gallery looks…

https://jimthoburn.github.io/photo-gallery/

## How to get this project running on your local machine

1) Install [Ruby and Jekyll](https://jekyllrb.com/docs/installation/)

2) Install [Node.js and NPM](https://nodejs.org/en/download/)

3) Run this command to install the dependencies for this project

```
npm install
```

## How to create your gallery

1) Choose your images and save them with numbers for the names. For example…

```
1.jpg
2.jpg
3.jpg
```

2) Place your images in the [images/original](https://github.com/jimthoburn/photo-gallery/tree/master/images/original) folder

```
/images/original/1.jpg
/images/original/2.jpg
/images/original/3.jpg
```

3) Update the config file with the name, date and number of images for your gallery.

```
title: Learn to Code LA
date: September 14, 2016
num_photos: 3
```

4) Run this command to generate and serve the website

```
npm start
```

5) View your gallery at [http://localhost:4000](http://localhost:4000)

6) When you’re ready to share it, upload the contents of the `_site` folder to your favorite web host!

You can also use [GitHub pages](https://pages.github.com).
