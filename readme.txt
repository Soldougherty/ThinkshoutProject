While I recognize that the easiest way to do this was probably to create a custom post type (especially if the use of a 3rd party plugin
like ACF was allowed), I took the approach I did because I don't have multiple years of wordpress experience, and I've never really dug
into it in this way before. I wanted to show my ability to learn, as well as take the opportunity to learn since I'd be spending my free time
on this anyway. To be honest, not a lot of it was particularly easy for me, and the majority of this was new to me. As the only time I had available
to work on this were the last several days, there are some things I would have liked to spend a little more time on, like changing the date format
after I realized I used the wrong one, or fixing my misunderstand on there needing to be a start/end time AND closed option, plus having a bit of
time to make the admin page look better. Even though a few things could be prettier and I didn't have time for any extra credit it does work so,
I'll take it.



Project outline:
-Create admin page
-Set up settings API (and then partway through realize register_setting isn't going to let me save multiple sets of form data, but why would anyone ever need to do that)
-Add HTML to settings callbacks
-Add HTML to admin page callback, add hidden form data
-Post to admin-post
-Save post data to db
-Populate admin table with saved form data
-Echo form data to admin-ajax
-validate, escape, sanitize
-Write javascript ajax request
-Add nonce to form and ajax request
-Jquery in some html, populate with request data
-Make it look kind of like the design I should have checked earlier
