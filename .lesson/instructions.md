# Instructions  

As you read through your [Django Web Framework (Python) readings](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django), you will use this replit to complete the Tutorials to create the Local Library Website example.

This replit uses Ubuntu as its command shell so when following along, use the instructions for Linux machines (sometimes, this will be shown as macOS/Linux as macOS is a UNIX system.)

While it's advised you read the article [Setting up a development environment](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/development_environment), this replit has been pre-set up for you through [Tutorial Part 2's Creating the Project section](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/skeleton_website#creating_the_project): your locallibrary directory and manage.py are all set up.

You can begin following along in the tutorial starting at [Creating the Catalog Application](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/skeleton_website#creating_the_catalog_application) in Tutorial Part 2.


## Running the repl
Setup a new secret environment variable (the lock icon located in Tools in your lefthand menu) where the key is `SECRET_KEY` and the value is a randomly generated token of 32 bits. 

1. Generate a 32 bit token by typing the below into the shell and hit Enter:
```
python
import secrets
secrets.token_urlsafe(32)
```
2. Copy the token
3. In the lefthand menu, under Tools click Secrets (Lock Icon) to create a secret.
4. Type `SECRET_KEY` as the key, the 32-bit token you generated as the value, and then click Add new secret.

You will now be able to run your repl. Another way is to type in your Shell ` python3 manage.py runserver`

See this 1 minute video for a walkthrough: [https://www.loom.com/share/ecc4e738149f4d1db3bcff01758b3e71](https://www.loom.com/share/341b5574d12040fb9fcbbff150777f1c)

## Submitting Your Work

Once you've completed the entire tutorial and have built the web application and it works, make sure you click Submit. You have until the due date posted in Canvas

Happy coding!