# packer-openstack-shutdown

This is a packer tempalte for testing the OpenStack builder and its terminate function. 

***Private data***
Copy the Example-privatedate.json to privatedata.json in the root of the directory. Add your own password and OpenStack auth here and the file will be ignored by git. Follow this practice for any other data you do not want in your repo.  

***Run the build***
<pre><code>packer build  -var-file privatedata.json shutdown_error.json</pre></code>
