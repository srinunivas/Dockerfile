ARG is a variable that users can a value at build time with docker build
ARG is used pass the variables at the time of images creation.

ENV is used to the variabes at timme of image and Cintainer creation. we can access the variable inside the container also, but with ARG, we ca only access the variables within the Image.

ARG is the only instruction you can use before FROM, ARG declared beforE cannot be accessed afrter FROM