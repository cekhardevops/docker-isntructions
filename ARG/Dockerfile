# ARG key value pairs only avaible at image build time. env pairs are avilable at both build image and container creation time
ARG course="Devops" \
    duration="120 Hrs" \
    version=9
FROM almalinux:$version
ENV course-env="Devops" \
    author="siva" \
    duration-env="120 Hrs"
RUN echo course:$course, duration: $duration, author: $author, course-env: ${course-env}, duration-env: ${duration-env}
CMD [ "sleep", "100" ]