FROM alpine:3.22.4

RUN apk add --no-cache curl bash

WORKDIR /app
COPY client.sh .

RUN chmod +x client.sh
CMD ["/bin/bash", "./client.sh"]