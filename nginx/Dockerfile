FROM nginx:stable

# SSL sertifikaları zaten host üzerinden mount edilecek
# Default conf'u sil
RUN rm /etc/nginx/conf.d/default.conf

# Config mount için hazır
CMD ["nginx", "-g", "daemon off;"]
