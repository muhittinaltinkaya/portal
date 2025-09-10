FROM nginx:stable

# SSL dizinini oluştur
RUN mkdir -p /etc/nginx/ssl

# Default conf'u sil
RUN rm /etc/nginx/conf.d/default.conf

# Config mount için hazır
CMD ["nginx", "-g", "daemon off;"]
