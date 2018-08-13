# RemoveExcessWhitespaceMiddleware
Laravel Middleware that removes excess whitespace from Blade

I took a look at https://gist.github.com/garagesocial/6059962 and realized that i could compress the output from Laravel blade with Middleware, iv edited this code for my own purpose and improved the compression of the HTML by adding an additional pattern.

Note this Middleware will cause some issues with layout which rely on a single white space to provide a margin between elements.

You can fix this behviour by adding a margin or &nbsp; to the effected elements
