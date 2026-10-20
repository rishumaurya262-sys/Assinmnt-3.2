# Assignment 3.2 — Images in HTML

## 1. Objective

The objective of this assignment is to learn how to add images to a portfolio webpage using HTML. It also helps us understand the `src`, `alt`, `width`, and `height` attributes of the `<img>` tag.

## 2. Project Folder Structure

Create the following folder structure in your project:

```text
web-development-practice/
│
├── index.html
│
└── images/
    ├── profile.jpg
    ├── web-development.jpg
    └── college-project.jpg
```

**Note:** Add three image files inside the `images` folder and give them the exact filenames shown above. You can use your own suitable images.

## 3. HTML Code

Create or update your `index.html` file with the following code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
</head>
<body>

    <header>
        <h1>My Portfolio</h1>
        <p>Welcome to my personal portfolio website.</p>
    </header>

    <nav>
        <a href="index.html">Home</a> |
        <a href="about.html">About</a>
    </nav>

    <hr>

    <main>
        <section>
            <h2>About Me</h2>

            <img
                src="images/profile.jpg"
                alt="Portrait photo representing the portfolio owner"
                width="250"
                height="250"
            >

            <p>
                Hello! I am a student learning web development.
                I enjoy learning new technologies and creating websites.
            </p>
        </section>

        <hr>

        <section>
            <h2>My Images</h2>

            <h3>Web Development</h3>
            <img
                src="images/web-development.jpg"
                alt="Computer screen displaying a website development workspace"
                width="400"
                height="250"
            >

            <h3>College Project</h3>
            <img
                src="images/college-project.jpg"
                alt="Student project materials arranged on a study desk"
                width="400"
                height="250"
            >
        </section>
    </main>

    <hr>

    <footer>
        <p>&copy; 2026 My Portfolio. All rights reserved.</p>
    </footer>

</body>
</html>
```

## 4. Explanation of the Image Attributes

| Attribute | Purpose |
|---|---|
| `src` | Specifies the path of the image file. |
| `alt` | Provides a meaningful text description of the image. |
| `width` | Sets the width of the image in pixels. |
| `height` | Sets the height of the image in pixels. |

For example:

```html
<img
    src="images/profile.jpg"
    alt="Portrait photo representing the portfolio owner"
    width="250"
    height="250"
>
```

The image is loaded from the `images` folder. The `alt` text describes the image for screen readers and provides a useful alternative if the image cannot load.

## 5. Steps to Complete the Assignment

1. Open your `web-development-practice` project folder.
2. Create a folder named `images`.
3. Add three image files to that folder.
4. Make sure their filenames match the paths in your HTML code.
5. Save the HTML file as `index.html`.
6. Open `index.html` in your browser.
7. Check that all three images load correctly.
8. If an image does not load, check its filename, file extension, and folder path.

## 6. Testing Checklist

- [ ] The `images` folder has been created.
- [ ] At least three images have been added.
- [ ] Every image has a meaningful `alt` attribute.
- [ ] The `src`, `width`, and `height` attributes are included.
- [ ] All image paths are correct.
- [ ] All images display properly in the browser.

## 7. Expected Result

The portfolio webpage should display an About Me section, a profile image, a Web Development image, and a College Project image. Each image should have an appropriate alternative text description.

## 8. Conclusion

In this assignment, I learned how to add images to an HTML webpage using the `<img>` tag. I also learned how to use the `src`, `alt`, `width`, and `height` attributes, organize image files in a separate folder, and verify that images load correctly in a browser.
