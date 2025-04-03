FROM almalinux:9
ENV course="new course" \
    trainer="ramakrishna" \
    duration="120HRS"
#here user1 is key, someuser is default value
ARG ${username:-some_user}
RUN echo "Hello ${username}" > /tmp/devops.txt
CMD [ "sleep", "100" ]