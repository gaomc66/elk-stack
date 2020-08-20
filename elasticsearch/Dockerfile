# build arguments, which are environment variables accessible only during the build process
ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:${ELK_VERSION}

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu
ARG ELK_VERSION
RUN echo "Build elk_version : ${ELK_VERSION}"
