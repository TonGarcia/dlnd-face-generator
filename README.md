# dlnd-face-generator
Last Udacity Deep Learning Nano Degree Project which generate faces using Adversarial Neural Network

Running Floyd:
1. Install
	```shell
		# python2
		$ pip install -U floyd-cli
		# python3
		$ pip3 install -U floyd-cli
		# anaconda python3
		$ source activate env-name && pip3 install -U floyd-cli
	```
2. LogIn
	```shell
		$ floyd login
	```
3. Setup
	```shell
		$ floyd init dlnd-translator
	```
4. Running
	```shell
		$ floyd run --cpu --mode jupyter --env tensorflow
		$ floyd run --gpu --mode jupyter --env tensorflow
	```

Running Docker:
1. Building it image:
```shell
    $ sudo docker build -t dlnd_tv_script_generation .
```
2. Running it __jupyter notebook__ into a container
```shell
    $ docker run -p 8888:80 dlnd_tv_script_generation
```
3. Running it __tensor board__ into a container
```shell
    $ docker run -p 6006:80 dlnd_tv_script_generation
```
