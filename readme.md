
Ensure you have docker with kubernetes enabled 

Run the following command 

- flytectl sandbox start

Then 

git clone https://github.com/mitzen/flyte-demo.git

cd flyte-demo 

pyflyte run --remote example.py training_workflow

browser to http://localhost:30081/console

you should be able to see an project called flytesnacks

