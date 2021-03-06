## User Manual

### Python Version 
python : 3.7.12

### Setup guide
1. Download python. (preferably 3.7)
2. Create virtualenv of python=3.7 in your system
```
virtualenv -p=python3.7 env_name
```
3. Install python libraries using requirements.txt
```
pip install -r requirements.txt
```

### Execution Guide
1. Execute following command to run diem v4.
```
python -m da -f -m src.orig num_replicas num_clients num_request f fail_idx logger_file_name > Test0.txt
```

da : To run DistAlgo file (.da), 

-f : Print logs on command line,

-m : run this file as a python module

### Command line args

num_replicas : number of replicas

num_clients : number of clients

num_request : number of requests generated by each client

f : nodes assumed to fail

fail_idx : node_id to be stopped 

logger_file_name : name of log file


### Run `run_config.sh` for running provided test cases 
