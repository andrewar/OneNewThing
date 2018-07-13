# OneNewThing
Learn one new thing, everyday.

# Programming
## Image processing

### Skimage - July 30, 2016
There's a scientific impage proessing library available for Python called skimage. This library is fairly straightforward. Some examples [here](http://scikit-image.org/docs/dev/user_guide/numpy_images.html "scikit").

of particular interest is accessing the image through an array:

~~~~~
>>> from skimage import data, io, filter
>>> image = data.coins()
>>> edges = filter.sobel(image)
>>> io.imshow(edges)
>>> io.show()
>>>
>>> camera = data.camera()
>>> camera[10,20]
153
~~~~~


### Postgresql jsonb and ActiveRecord - July 13, 2018
Postgres has a great jsonblob feature, allowing some functionality of a document store with the power of relational db:
https://robertbeene.com/rails-4-2-and-postgresql-9-4/



