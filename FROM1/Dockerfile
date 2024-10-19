ARG version
FROM almalinux:${version:-9}
# we can use the what what we want to give by using override
# we can override from outside
# command--> docker build -t arg:v1 --build-arg course=docker --build-arg version=8 .  
# here pulling 8 version
ARG course="DevOps with AWS" \
    duration="20hrs"
ENV duration=$duration    
RUN echo "Course: $course, Duration: $duration, Version: $version"
CMD ["sleep", "100"]
