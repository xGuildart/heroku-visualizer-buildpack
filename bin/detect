#!/bin/bash
# bin/detect <build-dir>

echo "at detect phase : build-dir=$1, current dir = $(pwd)"

if [ -f $1/frontend/package.json ]; then
  echo "React.js (create-react-app) multi" && exit 0
else
  echo "no" && exit 1
fi