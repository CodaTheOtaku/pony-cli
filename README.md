#!/bin/bash

season=$(printf '%02d' $1)

ep=$(printf '%02d' $2)

mpv --aid=1 https://yp.coco-pommel.org/ypvideo/YP-7R-${season}x${ep}.mkv
