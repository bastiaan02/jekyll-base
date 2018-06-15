### Can you set up a redirect from "/netlify/anything" to https://www.google.com/search?q=anything ?

``/netlify/* https://www.google.com/search?q=:splat``  
You can test the above redirect rule on this staging site: [https://staging--boilerman-alec-36888.netlify.com/](https://staging--boilerman-alec-36888.netlify.com/)
I set up a ``_redirects`` file with the above rule inside it.
