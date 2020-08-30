# Shaders and the first Triangle
Steps when we call CompileSHaders()

1. Create the shader and put it into Global ID. Create the program
2. Check for errors (normal check).
3. Add shader()  both vertex and fragment
	a) Create the shader
	b) Grab the code and put it into the shader.
	c) Compile it
	d) Add it to the program we defined.
4. Link the program. Check for linking errors.
5. Validate the program for the correct context. Check for errors.
6. Call the functions and draw the triangles.
