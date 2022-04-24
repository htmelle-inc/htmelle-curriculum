# Calculator Layout Project

In this project, we'll create a little gadget in the layout of a pocket calculator:

![complete](./images/complete.png)

You've already used all the tools you need to create this design. We want **you** to drive this. For
this project, try to code this one up and only use the video walkthrough if you get stuck!

The hardest part of this design will be the enter button. How can you make that button wider than
the others, but still have it align perfectly? That's up to you to discover. We recommend you save
that detail for last.

## Starter code

Use this starter code, `text-fira` is the font you'll be using:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://kit.fontawesome.com/638d441c12.js" crossorigin="anonymous"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Fira+Mono:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
    <title>calculator layout</title>
    <script>
      tailwind.config = {
        theme: {
          extend: {
            fontFamily: {
              fira: "Fira Mono, monospace",
            },
          },
        },
      };
    </script>
  </head>
  <body>
    Let's build a calculator layout
  </body>
</html>
```
