# hack-cville
repo for the cvill data challenge

* Install Docker and get Jupyter Notebook Running
	- Run `brew install docker`
	- Run `brew cask install docker`
	- Run the docker icon in the applications menu
	- Create a docker id and login
	- Login
	- Run `docker pull continuumio/anaconda3` to pull the docker image
	- Run `docker run -p 8888:8888 -i -t continuumio/anaconda3 /bin/bash` to create a docker container from the image
	- From within the docker image, run `jupyter notebook --ip 0.0.0.0 --no-browser --allow-root`
	- Go to the browser at localhost:8888 to access jupyter notebook. The first time you access it you will need to paste the token from terminal.
