FROM alpine:3.22.4

RUN apk add --no-cache curl bash

WORKDIR /app
COPY script.sh .

RUN chmod +x script.sh
CMD ["/bin/bash", "./script.sh"]