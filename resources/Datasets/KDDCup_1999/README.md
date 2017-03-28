# [KDD Cup 1999 Data](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)

## Abstract

This is the data set used for The Third International Knowledge Discovery and Data Mining Tools Competition, which was held in conjunction with KDD-99 The Fifth International Conference on Knowledge Discovery and Data Mining. The competition task was to build a network intrusion detector, a predictive model capable of distinguishing between `bad` connections, called intrusions or attacks, and `good` normal connections. This database contains a standard set of data to be audited, which includes a wide variety of intrusions simulated in a military network environment.

## Task Info

Software to detect network intrusions protects a computer network from unauthorized users, including perhaps insiders.  The intrusion detector learning task is to build a predictive model (i.e. a classifier) capable of distinguishing between `bad` connections, called intrusions or attacks, and `good` normal connections.

Attacks fall into four main categories:

1. DOS: denial-of-service, e.g. syn flood;
2. R2L: unauthorized access from a remote machine, e.g. guessing password;
3. U2R:  unauthorized access to local superuser (root) privileges, e.g., various `buffer overflow` attacks; 
4. Probing: surveillance and other probing, e.g., port scanning.

It is important to note that the test data is not from the same probability distribution as the training data, and it includes specific attack types not in the training data.  This makes the task more realistic.  Some intrusion experts believe that most novel attacks are variants of known attacks and the `signature` of known attacks can be sufficient to catch novel variants.  The datasets contain a total of 24 training attack types, with an additional 14 types in the test data only. 

For more info on task description: http://kdd.ics.uci.edu/databases/kddcup99/task.html

## Attack Types

|back 			|dos|
|buffer_overflow| u2r|
|tp_write 		|r2l|
|guess_passwd 	|r2l|
|imap 			|r2l|
|ipsweep 		|probe|
|land 			|dos|
|loadmodule 	|u2r|
|multihop 		|r2l|
|neptune 		|dos|
|nmap 			|probe|
|perl 			|u2r|
|phf 			|r2l|
|pod 			|dos|
|portsweep 		|probe|
|rootkit 		|u2r|
|satan 			|probe|
|smurf 			|dos|
|spy 			|r2l|
|teardrop 		|dos|
|warezclient 	|r2l|
|warezmaster 	|r2l|

## List of Features

|Features Name | Type|
|duration | continuous|
|protocol_type | symbolic|
|service | symbolic|
|flag | symbolic|
|src_bytes | continuous|
|dst_bytes | continuous|
|land | symbolic|
|wrong_fragment | continuous|
|urgent | continuous|
|hot | continuous|
|num_failed_logins | continuous|
|logged_in | symbolic|
|num_compromised | continuous|
|root_shell | continuous|
|su_attempted | continuous|
|num_root | continuous|
|num_file_creations | continuous|
|num_shells | continuous|
|num_access_files | continuous|
|num_outbound_cmds | continuous|
|is_host_login | symbolic|
|is_guest_login | symbolic|
|count | continuous|
|srv_count | continuous|
|serror_rate | continuous|
|srv_serror_rate | continuous|
|rerror_rate | continuous|
|srv_rerror_rate | continuous|
|same_srv_rate | continuous|
|diff_srv_rate | continuous|
|srv_diff_host_rate | continuous|
|dst_host_count | continuous|
|dst_host_srv_count | continuous|
|dst_host_same_srv_rate | continuous|
|dst_host_diff_srv_rate | continuous|
|dst_host_same_src_port_rate | continuous|
|dst_host_srv_diff_host_rate | continuous|
|dst_host_serror_rate | continuous|
|dst_host_srv_serror_rate | continuous|
|dst_host_rerror_rate | continuous|
|dst_host_srv_rerror_rate | continuous|

## Data Files

[A list of features](http://kdd.ics.uci.edu/databases/kddcup99/kddcup.names)
[The full data set (18M; 743M Uncompressed)](http://kdd.ics.uci.edu/databases/kddcup99/kddcup.data.gz)
[A 10% subset. (2.1M; 75M Uncompressed)](http://kdd.ics.uci.edu/databases/kddcup99/kddcup.data_10_percent.gz)

For your own exploration, the 10% subset data is enough. The file is in 'csv' format.