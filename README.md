Deep Learning environment used for examples and homework assignments in the Deep Learning course at University of Latvia.

Contains:  
   - tensorflow 1.6.0-rc1-py3
   - pytorch 0.3.1
   - gym 0.9.7

Course homepage https://estudijas.lu.lv/course/view.php?id=6693 is available only in Latvian. Press '__Pieslēgties kā viesim__' to login as a guest.

# Start CPU only container
1. `$ docker run -it -v "$(PWD):/notebooks/host_dir" -p 8888:8888 renarl/lu-dl-course`    
1. Copy access token `token` from the terminal output
1. Go to your browser on http://localhost:8888/?token=`token`

# Notes
## Preserving your notebooks between sessions
To preserve your work between sessions, save it in `host_dir`.

## Course examples
The examples from the LU DL course are in `lu-dl-course-examples`
