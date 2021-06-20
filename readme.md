# Running Nginx and Letsencrypt on Docker 

Follow instructions on [Automatic SSL with Let's Encrypt and nginx](https://dev.to/adamkdean/automatic-ssl-with-let-s-encrypt-nginx-4nfk)

## Problems with CSS loading

I had the issue that css was not forwarded correctly. The browser received the css files as 'text/html' instead of 'text/css'.
Could narrow it down to the redirect package used from the tutorial. Removing this container and everything worked well. 
