#Use an existing docker image as a base
FROM alpine
#Download and install dependency
RUN apk add --update redis
#Run default command/tell the image what to do when the container starts
CMD ["redis-server"]