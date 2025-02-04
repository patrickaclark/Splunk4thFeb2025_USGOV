### Splunk Generic architecture 

<img src="sparch.png">

### lab setup understanding 

<img src="labenv.png">

### SPlunk indexing and data storage

<img src="datas.png">

### searching data in searchhead 

<img src="sh.png">

# Splunk Restart 

### some basic info you need to know 

<img src="rest1.png">

## Splunk basic architecture 

<img src="sparch11.png">


### Splunk forwarder verify details 

### status 

```bash
/opt/splunkforwarder/bin/splunk status 
Warning: Attempting to revert the SPLUNK_HOME ownership
Warning: Executing "chown -R splunkfwd:splunkfwd /opt/splunkforwarder"
splunkd is running (PID: 784).
splunk helpers are running (PIDs: 1393).
[root@splunk-forwarder1 ~]# 

```

### checking Splunk Enterprise details 

```bash
/opt/splunkforwarder/bin/splunk list forward-server
Warning: Attempting to revert the SPLUNK_HOME ownership
Warning: Executing "chown -R splunkfwd:splunkfwd /opt/splunkforwarder"
Active forwards:
	10.160.0.2:9997
Configured but inactive forwards:
	None

```

### what is being monitored and forwarder by Splunk forwarder

```bash

 /opt/splunkforwarder/bin/splunk list monitor 
```

### creating Index and uploading data manually 

<img src="index1.png">

## Splunk dashboards 

<img src="dash11.png">

