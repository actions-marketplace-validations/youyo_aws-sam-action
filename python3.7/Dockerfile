FROM python:3.7-alpine

ENV SAM_CLI_TELEMETRY 0

RUN apk --update --no-cache add jq curl bash gcc musl-dev build-base libffi-dev

COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
