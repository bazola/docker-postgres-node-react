# docker-postgres-node-react

Steps to set up

1. Connect to your server (I'm using Ubuntu)

2. Install docker

3. Install docker-compose

4. Install npm

5. Create the react project with -- npm install -g create-react-app@3

6. Clone the repo into your project directory

7. Change the paths if needed

8. Run this command to create the persistent postgres volume -- docker volume create pgdata

When dependencies change, run npm install in the folder where package.json is located. node_modules is mounted inside the container, so the changes will be immediately reflected
