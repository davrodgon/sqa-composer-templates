FROM indigodatacloud/ci-images:python

LABEL maintainer="davrodgon@users.noreply.github.com"

RUN pip install PyGithub

COPY checkCitable.py /usr/local/bin/
RUN chmod +x /usr/local/bin/checkCitable.py  

ENTRYPOINT [ "/usr/local/bin/checkCitable.py" ]
