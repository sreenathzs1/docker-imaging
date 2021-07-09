FROM        ubuntu
RUN         apt update -y   
RUN         apt install nginx -y
# CMD         ["nginx", "-g", "daemon off;"]

ENTRYPOINT  ["nginx", "-g", "daemon off;"]
LABEL       company="zelarsoft" \
            employeename="sreenath r" \
            role="trainne"
            

# CMD & ENTRYPOINT are same working 
# CMD Will override the command