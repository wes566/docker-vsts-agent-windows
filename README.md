# docker-vsts-agent
Dockerfile for building windows vsts-agent

## how to build from repo
```
docker build github.com/wes566/docker-vsts-agent
```

## how to build locally
```
docker build .
```

## how to run
```
docker run -e VSTS_ACCOUNT=<acct name> -e VSTS_TOKEN=<token> -e VSTS_AGENT=<computer name> -it vsts_agent
```