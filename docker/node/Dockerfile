FROM node:24.12-alpine3.23

ENV COREPACK_ENABLE_DOWNLOAD_PROMPT=0
RUN corepack enable \
 && corepack prepare pnpm@latest --activate

WORKDIR /opt/apps
