# docker-compose
# what is docker compose
by using docker compose we can create multi services in one host
# Steps to create docker compose
# We have to install the docker compose packages by the command
sudo curl -L "https://github.com/docker/compose/releases/download/v2.17.3/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
![Screenshot 2024-11-07 154516](https://github.com/user-attachments/assets/7abff859-e01d-47fd-9d1d-ce4fb201fe42)
give the executable permissions by the command
sudo chmod +x /usr/local/bin/docker-compose
# to check the docker version
docker-compose –version
to add multiple services and we can create multiple containers by using only yaml file 
vi docker-compose.yml
![Screenshot 2024-11-07 162812](https://github.com/user-attachments/assets/4b38e863-5358-48bd-946b-8325bb7403f2)
we need to give the above commands
# To start compose file the command is
docker-compose up -d
![Screenshot 2024-11-07 162519](https://github.com/user-attachments/assets/fdff1057-9ebe-4c0a-82a4-54c088ea9799)
by using public ip we can start your image as soon in the above
To stop the container  the command is
docker-compose down
I want to get created image from docker hub by through yaml file as shown in below figure
![Screenshot 2024-11-07 164511](https://github.com/user-attachments/assets/65c0db6e-793b-41bc-b63c-8ab00a11f614)
then we need to run the yam file the commands
docker-compose up -d
to see the docker hub and all images we are using the command
docker-compose images
![Screenshot 2024-11-07 173325](https://github.com/user-attachments/assets/b3cf75b1-2d7e-47b7-b79e-5ea4478e0aff)






