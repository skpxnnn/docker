FROM alpine:latest                    
RUN apk add --no-cache bash           # Install Bash on Alpine
COPY script.sh /script.sh              
RUN chmod +x /script.sh               # Make your script executable
CMD ["/bin/bash", "/script.sh"]       # Use the full path to bash
