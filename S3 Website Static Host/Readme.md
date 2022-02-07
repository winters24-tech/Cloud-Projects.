# Used S3 to host a static website, added Route 53 to direct traffic to specific domain and added Cloudfront for caching and secure domain(HTTPS).<br>
### - Created my buckets, added my files of code, made the buckets publicly accessible and added a policy to make it available to the end user
![Screen Shot 2022-01-29 at 10 57 36 AM](https://user-images.githubusercontent.com/82731990/152718200-3620ef48-e00f-4b86-8f85-da512c9addec.png)
![Screen Shot 2022-01-29 at 6 57 46 PM](https://user-images.githubusercontent.com/82731990/152718224-726dc246-4f96-4e4c-a96c-65a4ad8e6429.png)
![Screen Shot 2022-01-29 at 7 02 32 PM](https://user-images.githubusercontent.com/82731990/152718230-c3e2af9c-73f3-4bd2-84fd-d8a227f0a504.png)
![Screen Shot 2022-01-29 at 7 04 11 PM](https://user-images.githubusercontent.com/82731990/152718236-da83ab29-665d-46ff-8ef4-152ec18c9544.png)
![Screen Shot 2022-01-29 at 7 04 35 PM](https://user-images.githubusercontent.com/82731990/152718239-c07912e8-82a9-416b-b3ba-db84710e5ab8.png)
### - Created a hosted zone in Route 53. My site wasn't available initially because it was a Google domain that I ended up transferring into AWS.
![Screen Shot 2022-02-03 at 9 32 43 PM](https://user-images.githubusercontent.com/82731990/152718272-b26cae99-ade7-44f8-8433-1f24ebec00d5.png)
![Screen Shot 2022-02-04 at 8 38 18 AM](https://user-images.githubusercontent.com/82731990/152718281-61796024-21c5-42ff-828b-781ec3b83e89.png)
### - Once I got the domain transferred I had to update the NS from the original Google ones to the updated AWS ones to have it work. (You can also see that the domain is not secured).
![Screen Shot 2022-02-04 at 8 38 42 AM](https://user-images.githubusercontent.com/82731990/152718290-5b892f58-7ce0-4e6a-9f1f-5051bcfa7a13.png)
![Screen Shot 2022-02-06 at 7 00 12 PM](https://user-images.githubusercontent.com/82731990/152718300-82d10ba7-f058-4443-a036-0a57df5ee08a.png)
### - I then created certificates for my Cloudfront distributions to not only make my domain secure but for caching for the end users.
![Screen Shot 2022-02-06 at 7 03 31 PM](https://user-images.githubusercontent.com/82731990/152718307-87a19f4d-95d7-47d6-bd8b-99fe9a9b46e3.png)
![Screen Shot 2022-02-06 at 7 19 15 PM](https://user-images.githubusercontent.com/82731990/152718338-3718b1fd-6751-4de6-bb77-a6f78a8b5b1f.png)
![Screen Shot 2022-02-06 at 7 21 32 PM](https://user-images.githubusercontent.com/82731990/152718351-65cc3517-bce3-4075-a0f7-d57b076343bc.png)
![Screen Shot 2022-02-06 at 7 26 52 PM](https://user-images.githubusercontent.com/82731990/152718357-114f60a3-e921-4a03-a947-e6c00db1d45e.png) <br>
## The End!
