#GLSL Tutorial
This is a XCode project with the GLSL examples from the [Lighthouse3s GLSL 1.2 tutorial](http://www.lighthouse3d.com/tutorials/glsl-tutorial/). These examples use the libraries GLUT and GLEW. The project assumes the GLEW library is installed in <code>/usr/local/bin</code>. You can install it here with homebrew:

```
brew install glew
```

If you use other location, you'll have to add <code>libGLEW.a</code> from the correct location to the 'Link Binary With Libraries' build phase and set the correct path in 'Headers Search Paths' for each target.

##Tartgets

Currently the following targets are included:

* setup - from the section 'Setup for GLSL – Example'
* uniform - from the section 'Uniform Variables'
* attribute - from the section 'Attribute Variables'
* attribute_array - also from the section 'Attribute Variables'

Only minor changes where made to the original source, essentialy the GLUT imports where changed to use the GLUT Framework in OSX, and some warnings where fixed. Some file names where changes to avoid colision between examples.