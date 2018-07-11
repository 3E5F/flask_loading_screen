# flask_loading_screen  
Example for implementing a loading screen for flask.  
 
## About   
If you're reading this, you're most likely just curious how to do a 'loading page' in flask.  
This is something I just slapped together. It should still be straightforward if you look through app.py . Just look through the code - any questions feel free to send me a message/email.

Note:
In my example, data is passed from the loading screen to the next page via URL where long-time processing can/will happen. At this point, the loading page has been loaded and is waiting for the processing to be done before the next page renders.

## Prerequisites
Make sure you have flask installed (use pip install)
`pip install flask`

## How to Run
`python python3_app.py` for Python 3 \
`python python2_app.py` for Python 2
