# use an existing docker image as base

FROM alpine

# Download and install dependency

RUN apk add --update gcc
RUN apk add --update redis

# Tell the image what to do when it starts
# as container

CMD ["redis-server"]
# "FROM, RUN" AND "CMD" are instructions telling Docker Server what to do