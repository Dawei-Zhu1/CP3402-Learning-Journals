# Week 5 - Word Press Child Theme

## Learning Activities & Resources

Here are the resources I used to help me understand how to use the child theme

1. JCU lecture videos and slides.
2. [Child Theme on WordPress.org](https://developer.wordpress.org/themes/advanced-topics/child-themes/)
3. [LinkedIn Tutorial](https://www.linkedin.com/learning/wordpress-building-child-themes-3/level-up-to-wordpress-developer?u=2223545)
4. [Responsive Design in Wordpress - LinkedIn Tutorial](https://www.linkedin.com/learning/learning-responsive-web-design-in-the-browser/welcome?u=2223545)

## Content Insights

A WordPress child theme can be regard as an add-on to its parent theme.
Along the way, some descriptive files are created to declare the relationship to the parent theme,
for example, it has child stylesheet(s), child scripts for additional functions and features.
In this way, developers are allowed to make changes on the parent theme 
instead of modify their source file directly. This makes all modifications to be 
The advantage of this mechanism is that developers can be speed-up the time in creating a theme,
and which can be applied to other pages that use the same parent theme, 
with predictable benefit of compatibility.

## Career/Employability/Learning Insights

While learning and practicing with child themes,
I did manage to quickly modify existing themes
to create my own style.
If you are an enterprise developer,
the advantages of using a child theme in terms of efficiency
and economy are very prominent. Especially in large projects.
It is possible to develop multiple child themes based on an existing WordPress theme
without worrying too much about conflicts or compatibility issues.
And it's good for future maintenance, as well.

But every coin has two sides. As I explored the way creating child themes,
I found that they have a downside during the development:
it only works well if the developer knows enough about the hierarchy of ut parent theme .
Therefore, as a new CMS developer, when creating a child stylesheet,
I had to look up the elements' tag names and styles
of the current theme in my browser's page inspector.
In some other cases, the styles I change might conflict with the parent theme's styles and they would not work.

In my opinion, creating and using child themes, while they do accelerate web development, 
is like dancing in shackles. Dancers still need to be experienced in order to perform beautifully. 
Just like I still need to learn the ways to use CMS.