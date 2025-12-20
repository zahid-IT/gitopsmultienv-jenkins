FROM nginx:alpine

LABEL maintainer="zahid bilal"
LABEL app="helm-argocd-demo"

COPY index.html /usr/share/nginx/html/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
