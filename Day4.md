# Phase 2 of WebDev Summer camp!

Today we are adding `CSS` to our websites! Do you know what CSS stands for?

### Open your website
- Make sure your flash drive is plugged in
- Open your File Explorer ( the yellow folder at the bottom corner ) 
- Find the **USB Drive** drive on the left side
- In your USB Drive, go into your website project folder
- Double click the `index.html` file
- In the web browser viewing your website **Right Click anywhere on the page** and then click **Inspect**. What do you see?

<hr>

### Open your website's HTML code

Open VS Code program. The icon looks like this:

![image](https://user-images.githubusercontent.com/38140593/178773893-4638681a-31ec-45b2-8aab-9348f2a77c16.png)

If you're `index.html` is not already there, follow this:

- In the top left corner, go to **File -> Open Folder**
- Find your USB Drive on the left side of the exploroer
- In there, find your website project folder
- Once you find it, click the folder then 'Select Folder' to continue


<hr>


### The HTML structure of a website is similar to human.

- Head
- Body
- Footer


### Let's add `<html>` and `<head>` tags to your website!

- In your `index.html` file, add the following:

```html
<!DOCTYPE html>
<html>
    <head>
    </head>
    <body>
        ...
    </body>
</html>
```


### Cool! Let's add a `<title>` tag

The `<title>` tag is very important! What is the title of your website?

- In your `<head>` tag, add a `<title>` tag with the title of your website inside
- After you add this, refresh your page....do you notice what changed?

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Your Website Title</title>
    </head>
    <body>
        ...
    </body>
</html>
```

### Let's add CSS!

The `<style>` tag is **awesome**!

- In your `<head>` tag, add a `<style>` tag. This is where we put our CSS

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Your Website Title</title>

        <style>

        </style>
    </head>
    <body>
        ...
    </body>
</html>
```

### HTML Finale! Let's add styles!

With CSS, you can change anything about your website!

- See everything you can change here: [https://www.w3schools.com/cssref/default.asp](https://www.w3schools.com/cssref/default.asp)

This is how CSS works:

- Declare a 'selector'
- Apply CSS styles to this 'selector'

This code means:
- For all `<p>` tags...
    - Change `color` to `red`
    - Change `font-size` to `60px`

```html
<style>
p {
    color: red;
    font-size: 60px;
}
</style>
```

