# Live-Video-Stream-from-Raspberry-Pi-Camera-over-the-Network

Simple code in python using openCV and Socket for live video stream from Raspberry Pi Camera

## Dependencies

1. Python 3
2. opencv (above 3.3) in server (Ubuntu Tested)
3. Pillow in server (Ubuntu Tested)
4. Numpy in server (Ubuntu Tested)
5. Picamera in Raspberry Pi

## Run 

In Server (Ubuntu):
```
Python3 pi_video_server.py 0.0.0.0 port_no
```

In Raspberry Pi:
```
Python3 pi_video_client.py server_ip port_no
```

## Authors

**Arijit Das** 


## Acknowledgments

* https://picamera.readthedocs.io/en/release-1.10/recipes1.html
