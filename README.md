# Portfolio project

A portfolio-webpage as part of an assignment on Udacity. Given a design-template
as a `.pdf` I was tasked to replicate the design as a responsive webpage.

The design can be found here: [PDF Template](design-mockup-portfolio.pdf)

## Inntallation

The images needs to be generated by the grunt-script. Do do this, make sure you
have `node` and `grunt` installed. See [Grunt's Getting Started
Guide](http://gruntjs.com/getting-started) for more information regarding this.

After that, run the following command inside this project's directory:
```
npm install
```

Now you are all set to create the images. This can ge done by simply running

```
grunt
```

and it will generate the images in the correct sizes for both the icons and the
pictures.

Now you can either create a HTTP-server, either using python and the command
below, or any other way you feel comfortable with.

```
python -m SimpleHTTPServer
```

## Design

### Desktop
![Desktop design](http://i67.tinypic.com/t6ci0j.png)

### Smaller screens
![Design for small widths](http://i65.tinypic.com/351icf7.png)

### Modal view

Each of the items has clickable images and headlines which opens a modal view
using bootstrap ![Design for small widths](http://i64.tinypic.com/aky0ph.png)
