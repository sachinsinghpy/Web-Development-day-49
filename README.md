# Web-Development-day-49
CSS Object Fit and Position
The CSS object-fit Property
The CSS object-fit property is used to specify how an <img> or <video> should be resized to fit its container.

This property tells the content to fill the container in a variety of ways; such as "preserve that aspect ratio" or "stretch up and take up as much space as possible".

Here is where the object-fit property comes in. The object-fit property can take one of the following values:

fill - This is default. The image is resized to fill the given dimension. If necessary, the image will be stretched or squished to fit
contain - The image keeps its aspect ratio, but is resized to fit within the given dimension
cover - The image keeps its aspect ratio and fills the given dimension. The image will be clipped to fit
none - The image is not resized
scale-down - the image is scaled down to the smallest version of none or contain

Using object-fit: cover;
If we use object-fit: cover; the image keeps its aspect ratio and fills the given dimension.The image will be clipped to fit.


Using object-fit: contain;
If we use object-fit: contain; the image keeps its aspect ratio, but is resized to fit within the given dimension.

Using object-fit: fill;
If we use object-fit: fill; the image is resized to fill the given dimension. If necessary, the image will be stretched or squished to fit.

Using object-fit: none;
If we use object-fit: none; the image is not resized.


Using object-fit: scale-down;
If we use object-fit: scale-down; the image is scaled down to the smallest version of none or contain:


CSS The object-position Property
The CSS object-position property is used to specify how an <img> or <video> should be positioned within its container.


CSS Object-* Properties
The following table lists the CSS object-* properties:

Property	Description
object-fit	Specifies how an <img> or <video> should be resized to fit its container
object-position	Specifies how an <img> or <video> should be positioned with x/y coordinates inside its "own content box"

