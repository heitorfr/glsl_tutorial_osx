GLSL Tutorial
============
This is a XCode project with the GLSL examples from the [Lighthouse3s GLSL 1.2 tutorial](http://www.lighthouse3d.com/tutorials/glsl-tutorial/). It assumes the GLEW library installed in <code>/usr/local/bin</code>. You can install it here with homebrew:

```
brew install glew
```

If you use other location, you'll have to add <code>libGLEW.a</code> from the correct location to the 'Link Binary With Libraries' build phase and set the correct path in 'Headers Search Paths' for each target.

Currently there are two targets correcponding to the firts two tutorial examples:

* ogl - from the section 'Setup for GLSL – Example'
* ogl3 - from the section 'Uniform Variables'

Only minor changes where made to the original source, essentialy the GLUT imports where changed to use the GLUT Framework in OSX, and some warnings where fixed.