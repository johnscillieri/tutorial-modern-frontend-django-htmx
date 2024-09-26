# Tutorial: Django HTMX and friends 

Once upon a time, if you wanted to build a modern frontend web experience using a Python based web framework, an obvious choice was to expose a bunch of APIs and build your frontend in something else entirely (eg React).

Times have changed.

Tools like HTMX and AlpineJS have made HTML great again.

These tools make full stack web dev fast and fun, they simplify development, shrink code bases, and give backend devs the ability to do modern frontend work. In my personal experience I've seen the adoption of these tools lead to massive productivity gains for junior and senior devs alike.

This workshop will walk you through the process of building and testing a CRUD application with a rich and modern frontend.

As we build this out, you will implement a few patterns for handling some of web development’s most common frontend requirements. For example, hydration.

We'll be making use of:

- Django
- HTMX
- a sprinkle of AlpineJS
- a touch of of Tailwindcss
- Playwright for testing

Even though this is a Django-based tutorial, we wont be covering any super advanced Django functionality. Our focus will be on the frontend, and testing the frontend.

If you would like to see what these tools are about, here are a few talks:

- [DjangoCon 2022 | From React to htmx on a real-world SaaS product: we did it, and it's awesome!](https://www.youtube.com/watch?v=3GObi93tjZI)
- [DjangoCon US Keynote: Testing Modern Web Apps Like a Champion with Andrew Knight](https://www.youtube.com/watch?v=Ze62p97coaY)

## Directory structure

There are 3 directories to know about:

1. tutorial 
2. demo 
3. presentation

### 1. Tutorial

This is where the magic is at. This is a series of markdown files that walk you through all the things. Start at the top. 

### 2. Demo

This is the application that gets built up during the demo. You can poke around here to see the finished product of what we are doing. 

### 3. Presentation

This repo was originally created as a tutorial to be run during the excellent PyConZA conference. The presentation in place introduces the topic, but also introduces the original tutorial presenter human (Sheena O'Connell).

If you are reusing this content, please feel free to consider the presentation a placeholder or example and adapt it as needed.

The presentation was created using [reveal.js](https://revealjs.com/). Reveal.js is a presentation framework. It rocks and you can make really nice things quite quickly with it. 