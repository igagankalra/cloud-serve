FROM ubuntu
RUN apt-get update -q
RUN apt-get install -y curl
COPY sitetest.sh sitetest.sh
CMD ["/sitetest.sh"]