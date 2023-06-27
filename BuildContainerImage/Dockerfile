# The image of the container
FROM golang:1.13
# Which files to copy
COPY main.go .
# A command to run while building the container
RUN go build -o /server
# The command that get's executed when the container starts
CMD ["/server"]