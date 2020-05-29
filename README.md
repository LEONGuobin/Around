# Around

This is a twitter-like app for users to post their daily life. The main function includes posting messages, posting images 
and other media forms. And people can search the posts through geolocation and face recognition. 

In this project, Golang was used as the programming language of backend to deal with the remote procedure call such as post and 
search. GCS was used to store the media files. Elastic Search was also used as a no-sql database to store the messages, geolocation 
and link of media files. Face recognition is also a interesting part. It uses the Google Vision Api so the app can recognize the
human face and elastic search can search out the cluster of posts that contain human face. Token-based authorization was also created 
to make backend stateless and more mobile-friendly.

The front-end has not been built alread. I'm going to use React to do the following steps.

The project was packed up in the Docker and deployed on Google Kubernetes Engine, which can deploy the app into a distributed 
system automatically. 
