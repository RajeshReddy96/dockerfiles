ARG version
FROM almalinux:${version}
# we can use the what what we want to give by using override
# we can override from outside
ARG course="DevOps with AWS" \
    duration="20hrs"
RUN echo "Course: $course, Duration: $duration"
CMD ["sleep", "100"]
