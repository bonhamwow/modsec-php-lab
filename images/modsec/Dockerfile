FROM owasp/modsecurity-crs:nginx
USER root
RUN apt-get update && apt-get install -y iproute2 && rm -rf /var/lib/apt/lists/*