# task-scheduler
## Steps to setup
Install rabbitmq : sudo apt-get install rabbitmq-server<br />
Install celery : pip install celery

## Execution
Run the celery worker server : celery -A tasks worker --loglevel=INFO <br />
Run test.py and observe celery server for output

## References 
[Celery Documentation](https://docs.celeryq.dev/en/stable/index.html)
