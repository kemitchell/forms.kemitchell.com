#!/bin/sh
npx http-server -p 8080 . &
trap "kill -9 $!" EXIT
npx broken-link-checker "http://localhost:8080"
