ARG version
FROM almalinux:${version:-9}
ARG USERNAME=jai
ENV USERNAME=$USERNAME
RUN echo "Hi,I am ${USERNAME} and version ${version}">/tmp/devops.txt
CMD ["sleep","100"]