# mean_docker

# To build docker conatainer
$ docker build

    '''''
    
    '''''
    successfully built <random-number-called-it-x_num>
   
$ docker run --name < choose any name > <x_num>

# in new terminal

$ docker exec -it < container-id > /bin/bash

 |__
 
    $cd /usr/src/app/djangoapp
    $python manage.py runserver
    
# now you can open this project in browser 
