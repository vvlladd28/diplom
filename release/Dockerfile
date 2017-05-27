FROM nextcloud:latest
COPY ./onlyoffice /var/www/html/custom_apps/onlyoffice
COPY docker-entrypoint2.sh /root/entrypoint.sh
RUN chmod +x /root/entrypoint.sh
ENTRYPOINT ["/root/entrypoint.sh"]

