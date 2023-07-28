Project Features : 
User will enter the long URL in the input form
User can see the details after making the long URL into a short URL in a tabular format
User can copy the short URL link by clicking the copy button
If a user tries to access the short URL after 2 years, the link will be broken

In the backend : 
We are using base62 to make the shortcode for our short URLs
In the database, the long URL and short URL links will be saved
Whenever a user hits the short URL, it will redirect to the actual URL 
The short URL will be deleted due to inactivity of almost 2 years
We have added a simple javascript code for coping the short link
