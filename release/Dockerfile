FROM nextcloud:latest
COPY ./onlyoffice /var/www/html/custom_apps/onlyoffice
COPY docker-entrypoint.sh /root/entrypoint.sh
RUN chmod +x /root/entrypoint.sh
ENTRYPOINT ["/root/entrypoint.sh"]
CMD ["apache2-foreground"]

