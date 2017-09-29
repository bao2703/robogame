## PREREQUISITES
1) Install [Docker](https://www.docker.com/)
2) Open command-line tool, change directory (cd) to your project

## HOW TO RUN

```
docker run -it --rm -v `pwd`:/src bao2703/opencv
```

### EXAMPLE

To detect lanes lines on the video 'challenge.mp4':

#### RUN `python3 lane_lines.py -i videos/challenge.mp4 -o output.mp4`

To detect lane lines on a single image (e.g. for debugging):

#### RUN `python3 lane_lines.py -i input_image.jpg -o output_image.jpg -I`