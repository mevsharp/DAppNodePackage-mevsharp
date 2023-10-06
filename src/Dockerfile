ARG UPSTREAM_VERSION
FROM mevsharp/mevsharp:${UPSTREAM_VERSION}

COPY entrypoint.sh /usr/local/bin/entrypoint.sh

ENTRYPOINT [ "/usr/local/bin/entrypoint.sh" ]