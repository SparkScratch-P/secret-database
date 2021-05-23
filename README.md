 # WebSheild
A web-based URL shield to protect your shared cloud storage link from unauthorised access.
---

 It works as creating a web page that acts as the sheild between the search-engine and another web page (part of this project) that will lead to a link for the target data. This may be used as a security sheild to protect cloud data of an institution, intelligence, sensitive data or personal data of special interests. One can easily secure files with this toolkit.
  This simple HTML document helps you protecting static pages or whole websites with no server configuration required: you can now use Dropbox, Amazon S3 or any generic hosting service to host a private, password protected site.
  
 ## Check out:
 
- Go to https://sparkscratch-p.github.io/secret-database/
- Try with Password `vikrampanchabinshati`
 
 ## Create Your own Database
 
 After having this page forked , go to ur repo and follow the steps:
 
 To Host this from somewhere else, follow these steps:
 
 - Upload the `index.html` document and the background image to your static hosting service.
 - Open a [SHA1 Generator](https://emn178.github.io/online-tools/sha1.html) and create the SHA1 hash of ur desired password.
 - Create a folder with that SHA1 has as the name in the same directory as 'index.html' file.
 - Inside the folder, upload another `index.html` (U can upload any index file a per your choice) file, as here in the `eb91ac12a134626cc4d4e84ec5ff4d338cf2fedb` directory.
 - Make necessary edits in that `index` file. ***If you are using my file, just put the link to be secure in places of `my URl` and edit txts as required.***

The final structure will be:

```
- index.html
- background.jpg
- this-is-a-hash      <-- the SHA1 hash of your password               
  \ - index.html      <-- your original index document
  ```
  
 ##  Is this secure?
 
Pretty much secure, please consider that:

- If your hosting service offers directory listing, a visitor can bypass the protection.
- There's no protection against brute force attack. Pick a very long and hard to guess password.
- The password's hash is part of the URI. Enforce HTTPS to avoid man in the middle attacks.

## Troubleshooting

- Test the demo page in your browser with password 'secret'
- Deploy the whole repo on your hosting, and test again.

## Licence

[GNU General Public License v3.0](https://github.com/SparkScratch-P/secret-database/blob/main/LICENSE)

# Enjoy the SPARK Security!!!
 
