FROM almalinux:8
ARG username
RUN adduser $username
USER $username
ARG trainer 
ARG duration 
RUN echo "trainer:${trainer},duration:${duration}"
ENV trainer=${trainer}
ENV duration=${duration}
CMD ["sleep","100"]