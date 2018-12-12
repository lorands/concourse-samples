# Concourse conditional

I assume that you already have a s3 bucket in AWS for this example. 
My bucket is called ``concourse-build`` where I have a ``sample`` folder. 
The credentials for accessing AWS for me are stored in vault/credhub 
with keys: ``aws-access-key-id`` and ``aws-secret-access-key``, but you can 
define them directly or resolve from yml.


