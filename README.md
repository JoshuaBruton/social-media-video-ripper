# 🫂 Social Media Video Ripper 🎥 ✂️

![Screen Shot 2025-02-02 at 2 35 54 PM](https://github.com/user-attachments/assets/bc6c0bf0-8c7f-4324-a032-f072d145b681)

Simple but elegant CLI script that prompts the user for a url to a video on pretty much any social media platform (tested to work for Facebook and Twitter(X) - tho I'm sure it would work for others as well). 


### To use this yourself: 


~ $ git clone https://github.com/BRuDesDev/social-media-video-ripper.git  # Clone the repo to your local machine.
~ $ cd social-media-video-ripper # Enter the newly cloned folder.

~ $ python3 -m venv .venv  # Create Python virtual environment  
~ $ source .venv/bin/activate  # Activate the virtual environment

### Now that we are inside our Python virtual environment, we can install our requirements using pip
~ $ pip install -r requirements.txt  
### Then all you have to do:
~ $ python3 sm_dl.py 

The user can then copy & paste any video 'url' you wish to save - press Enter - you will be asked for one more input, and that's for you to name the video file. Once you enter that, you can see the download in the terminal as well as a finished message.

You will find the downloaded video in a folder called **videos** in the apps root dir, unless you changed that within the script.
