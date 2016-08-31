mapr-opentsdb
=========

Install opentsdb with MapR DB as backend.

Requirements
------------

You need a MapR cluster. This will work with either the free community edition or the enterprise database edition.

Role Variables
--------------

Set the hbase version and hadoop version using hbase_version, hadoop_version and also mapr_version

Dependencies
------------



Example Playbook
----------------

	- hosts: hbasemaster
	  roles:
	    - { role: mapr-opentsdb, hbase_version: 1.1.1, hadoop_version: 2.7.0, mapr_version: v5.1 }

License
-------

MIT

Author Information
------------------

Vince Gonzalez, Buğra Çakır
