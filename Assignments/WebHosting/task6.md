## Task 6 - S3 HTTP Hosting

Complete the following tutorial to host a **static** website on S3.  You are welcome to look up additional tutorials that have more pictures.

Name your bucket `yourlastname.com`

[Tutorial: Configuring a static website on Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/HostingWebsiteOnS3Setup.html)

Add your static web content files to the S3 bucket.  There needs to be a minimum of an `index.html`, `404.html`, and referenced content (image file(s) or `css` file(s))

On March 9th, 2024, I left my future self a note - "AWS has a default page. Be specific if you want non-default index.html" So watch out for that.

## Documentation

Honestly it just doesnt work and i can only use 30% of my brain power when im sick
![image](https://github.com/user-attachments/assets/c544ec0b-6885-43cd-9cd3-15216cd5b131)



Create a folder in your course GitHub repository called `Web-Hosting`.  Create a file named `s3-hosting.md` and insert the following details.

- Link to tutorial(s) used to setup or your bucket or assist with troubleshooting
- https://stackoverflow.com/questions/40046072/access-denied-on-aws-s3-bucket-with-no-permission-set-up
- https://us-east-1.console.aws.amazon.com/s3/buckets?region=us-east-1&bucketType=general
- https://aws.amazon.com/awstv/watch/9beeb827905/
- even asked chatgpt and still got nothing.
- Test your index.html by visiting the site URL.  Document the URL
- Test the error page by requesting a file / resource that does not exist in your bucket.  Document a URL that will resolve to your `404` page 
- Research and document the AWS recommended way to associate a Domain name with your S3 bucket
- 
- Research and document the AWS recommended way to enable HTTPS
- https://docs.aws.amazon.com/AmazonS3/latest/userguide/website-hosting-custom-domain-walkthrough.html
Amazon S3 does not support HTTPS access to the website. If you want to use HTTPS, you can use Amazon CloudFront to serve a static website hosted on Amazon S3.
## Submission

Submit a link in Pilot to your course GitHub repository with your S3 hosting documentation.
