# Blaze-CSS

Blaze CSS is a CSS utility class library that shortens the process of styling elements, while mostly staying in the HTML.

Obviously, you have already seen my website. Otherwise, you would not be here.

As a reminder, Blaze CSS is an experiemental and still-in-development project of mine. In addition to that, I am a 14 year old programmer with very little knowledge of programming compared to a professional.

In the future, I look forward to updating Blaze CSS with new features.


DOCUMENTATION:

In HTML, an element should look something like this:
<p id="text-element" class="text-info" style="styling here...">
Of course, you could have an external CSS file or inline styling in your HTML file, but it takes a short amount of time to switch between HTML and CSS. This is where Blaze CSS comes in.
In HTML, you can add multuple identifying class names to one element. Blaze takes advantage of this, by making it so that you can add styling directly to the classes.
  
Blaze CSS is formatted something like this:
  
.big-text{
  font-size: 100px; 
}
  
There is a dot at the beginning because it is the class identifier type. Next, the class name. This is what you would put in your element's classes. Then, there is a style that is in-between the curly braces. This is the style that is given to the element.
  
<p class="big-text">BIG TEXT!!!</p>

^^^ this is what a element with Blaze CSS would look like.

Also, you can add more than one class name to an element.
