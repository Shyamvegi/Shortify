# Shortify

This service will provide short aliases redirecting to long URLs.

# System Requiremnts

Our URL shortening system should meet the following requirements:  

## Functional Requirements:

1. Given a URL, our service should generate a shorter and unique alias of it. This is called a short link. This link should be short enough to be easily copied and pasted into applications.  
2. When users access a short link, our service should redirect them to the original link.  
3. Links will expire after a standard default timespan that is 15 days.  

## Non-Functional Requirements:

1. The system should be highly available. This is required because, if our service is down, all the URL redirections will start failing.  
2. URL redirection should happen in real-time with minimal latency.  
3. Shortened links should not be guessable (not predictable).  

## Extended Requirements:  

1. Our service should also be accessible through REST APIs by other services.  


# Using urlShortner

To use urlShortner, follow these steps:

Note: Don't forget change your redis hostname and port no.

```
git clone https://github.com/Shyamvegi/Shortify.git
cd Shortify
cd server
npm install
npm start
cd ..
cd client 
npm install
npm start 
```

Add run commands and examples you think users will find useful. Provide an options reference for bonus points!

# Contributing to urlShortner
<!--- If your README is long or you have some specific process or steps you want contributors to follow, consider creating a separate CONTRIBUTING.md file--->
To contribute to Shortify, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.


