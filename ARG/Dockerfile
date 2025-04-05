ARG version
FROM almalinux:${version:-9}
ENV course="new course" \
    trainer="ramakrishna" \
    duration="120HRS"
#here user1 is key, someuser is default value
ARG USERNAME=ramakrishna
RUN echo "Hello ${username}, image version: ${version}" > /tmp/devops.txt
CMD [ "sleep", "100" ]