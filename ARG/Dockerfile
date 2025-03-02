ARG version
#If i don't give any version number, default value(9) will be taken.
FROM almalinux:${version:-9}
ENV course="Devops" \
    trainer="Siva"
#ARG same like ENV, key:value pair.
ARG USERNAME=Vamshi
RUN echo "Hello User: ${USERNAME}, image version : ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]