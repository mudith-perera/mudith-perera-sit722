# syntax=docker/dockerfile:1

FROM nginx:1.27-alpine
WORKDIR /usr/share/nginx/html

# Copy static site (adjust if you have more assets)
COPY index.html .
COPY main.js .
# COPY assets/ ./assets/
# COPY styles.css .

# Optional: use a custom nginx.conf if you have one
# COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
