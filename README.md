Deep Learning environment used for examples and homework assignments in the Deep Learning course at University of Latvia

Contains:
- tensorflow 1.6.0-rc1-py3
- pytorch 0.3.1
- gym 0.9.7

# Start CPU only container
1. `$ docker run -it -p 8888:8888 renarl/lu-dl-course`    
1. Copy access token `token` from the terminal output
1. Go to your browser on http://localhost:8888/?token=`token`
