# S3 Static Website Lab

**Goal:** Host a simple static website on Amazon S3.

## Steps I followed
1. Created an S3 bucket.
2. Uploaded my `index.html` file.
3. Enabled static website hosting in the bucket properties.
4. Made the bucket public so I could access the site from a browser.
5. Tested the site using the S3 website endpoint.

## What I learned
- How to host a static website on S3.
- How to configure bucket permissions for public access.
- How to view the site using the S3 website URL.

## Example website code
```html
<!doctype html>
<html>
<head>
  <title>Claire's S3 Static Website</title>
</head>
<body>
  <h1>Hello from my first AWS S3 Static Website!</h1>
  <p>This site was hosted on Amazon S3 as part of my AWS SA lab.</p>
</body>
</html>







