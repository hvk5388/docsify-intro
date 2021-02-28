Structure
How does 11ty Structure Data?
11ty has zero boilerplate client-side JavaScript. Basically that means that it doesnt use a JavaScript framework. The build routine process takes the files and compiles them into just HTML/CSS. Because of this you have a lot more flexibility in what you use.

It runs files purely based on their location in the file system. The file system is used to create this pattern or hierarchy of content. In this site there is am index.html that uses its folder structure to create a menu structure.

11ty is zero-config which means that it works with your projects existing directory structure. This gives flexible configuration options. It just uses what you specify in your template formats configuration. The data cascade layer uses independent template engines. You can be more flexible in what youre using and not required to work only with 11ty, but with any open source you want. Your data can be used on a template from anywhere.

Flexibilty
This seems to be 11ty's favorite word. They don't want users to be tied to a specific CMS for everything they do. This is why the embrace so 