# Use the official Golang image
FROM golang:1.16

# Set working directory
WORKDIR /backend

# Copy the local Go files into the container
COPY . .

RUN go mod download

# Build the Go application
RUN go build -o backend

# Run the application
CMD ["./backend"]

