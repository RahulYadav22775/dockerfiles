ARG version
FROM almalinux:${version:-9}
ARG course="devops with aws" \
    duration="120hrs"
ENV duration=${duration} \
    course=${course}
RUN echo "course is : ${course} , duration is : ${duration}, version is : ${version}"
CMD ["sleep", "100"]