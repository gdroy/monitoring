# Work around for missing findutils reference - https://github.com/google/cadvisor/issues/1641
FROM google/cadvisor
RUN apk add --update findutils && rm -rf /var/cache/apk/*
