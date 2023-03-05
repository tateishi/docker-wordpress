FROM filebrowser/filebrowser

RUN mkdir /config && chown xfs:xfs -R /config
USER xfs
COPY filebrowser.json /config


ENTRYPOINT ["/filebrowser", "-c", "/config/filebrowser.json"]