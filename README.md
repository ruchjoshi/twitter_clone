# Django Twitter Clone by Ruchir Joshi

Fully functional Django App that looks like real Twitter.

To install and run:
Make sure you have python installed on your system
Download all the files and navigate to the project directory
create a virtual environment and then inside the virtual environment,
run the command 'pip install -r requirements.txt'
Next, run the commands 'manage.py makemigrations' and then
'manage.py migrate' and lastly 'manage.py runserver'

To run the chat application with websockets, first install docker on your system
then in the command line or bash shell run the command
'docker run -p 6379:6379 -d redis:5'
Then run the server using 'manage.py runserver'

You should now have a fully functioning twitter clone with chat rooms
hosted on your own server!
