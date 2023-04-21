# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY Program1_2.c .
# Compile the C program
RUN gcc -o Program1_2 Program1_2.c
# Set the command to run when the container starts
CMD ["./Program1_2"]