
Ensure you have docker with kubernetes enabled 

Run the following command 

- flytectl sandbox start

Then 

git clone https://github.com/mitzen/flyte-demo.git

cd flyte-demo 

pyflyte run --remote example.py training_workflow

browser to http://localhost:30081/console

you should be able to see an project called flytesnacks

Some of the default projects created by flyte

![alt text](https://github.com/mitzen/flyte-demo/blob/main/1.png?raw=true)

You can see we have a tasks under a workflow 
![alt text](https://github.com/mitzen/flyte-demo/blob/main/2.png?raw=true)

Tasks that are being run and you can see we can re-run some of it
![alt text](https://github.com/mitzen/flyte-demo/blob/main/3.png?raw=true)
