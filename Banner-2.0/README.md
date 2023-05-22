## Banner 2.0
1. Banner 2.0 is a platform for students, professors, and advisors that combines course registration and transcript viewing.
1. Link to the video is https://drive.google.com/file/d/1vDjbuMqai9PV2ad3UJRoFSSqupz_DG3g/view?usp=share_link

## How to start the program
**Important** - you need Docker Desktop installed

1. Clone this repository.  
1. Create a file named `db_root_password.txt` in the `secrets/` folder and put inside of it the root password for MySQL. 
1. Create a file named `db_password.txt` in the `secrets/` folder and put inside of it the password you want to use for the `webapp` user. 
1. In a terminal or command prompt, navigate to the folder with the `docker-compose.yml` file.  
1. Build the images with `docker compose build`
1. Start the containers with `docker compose up`.  To run in detached mode, run `docker compose up -d`. 

