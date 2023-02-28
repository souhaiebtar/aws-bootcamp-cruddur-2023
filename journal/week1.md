# Week 1 — App Containerization

after i watched the video about container best practices, i tried to apply them to the context of our application,
more precisely i added a specific user `app` and i switched to it, also i added a new endpoint `/health` that gonna be used
to health check the backend app, for that i also needed to install `curl` and  i removed the `apt` cache so that i minimize the size of the image

![dockerBestPractices][dockerBestPracticesApplied]

the next screenshot is about the source code for the `/health` endpoint, generaly it should be public (not behind authentication)
and it should verify if app is healthy (for example by verifying the main component of an application)

![newHealthEndpoint][healthEndpoint]



[dockerBestPracticesApplied]: assets/1-dockerBestPractiseAndHealthCheck.png
[healthEndpoint]: assets/1-health-endpoint.png