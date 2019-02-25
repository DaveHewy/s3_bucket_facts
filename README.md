AWS S3 Bucket Facts
=========

Sets facts on a given found S3 bucket

Role Variables
--------------

- name

Example Playbook
----------------

```
- s3_bucket_facts:
    name: example-s3-bucket

- assert:
    that:
     - s3.name == 'example-s3-bucket'
```

License
-------

BSD

Author Information
------------------
David Heward
