# DESIGN WEBPAGE - PRACTICE 👩‍💻

Practicing HTML and CSS with Figma Design Files are simply great and learning them by doing it is very much helpful while learning things.

![Front End Mentor - QR code Component](./preview.jpg)

This project was really made me understand how design files need to be distributed with a team. Making use of Figma is making the Coding process more easy and let me make strategies regarding the Design pattern.

## THINGS I LEARNED

1.  How to make use of [`figma`](https://figma.com) design tool to understand components.
1.  This exercise let me learn how to build the project on my own.
1.  Learn the Article on using Figma.
1.  Separated my Mobile and Small screen CSS queries using `@media` query in a separate file.

I have noticed that the order of placing the QR code is important while rendering the page. Here the Queries.css file contains the changes related to Mobile and Smaller Screens. It is important to have `queries.css` below the `style.css` file to make sure it is getting updated over the `style.css` files.

```
<!-- Custom CSS -->
<link rel="stylesheet" href="style.css" />
<link rel="stylesheet" href="queries.css" />
```

I have learned build to Fit Object's using CSS

```
<!-- QR Code Image Container -->
.img-container {
border-radius: 20px;
overflow: hidden;
}

/* Image QR Code */
img.qr-code {
width: 100%;
object-fit: scale-down;
object-position: 50% 50%;
}
```

## IMPORTANT LINKS

Live Page: [Page on GitHub](https://logeshwaran123.github.io/qr-code-component/)<br/>
Codebase: [Repo Link for GitHub](https://github.com/Logeshwaran123/qr-code-component.git)<br/>
