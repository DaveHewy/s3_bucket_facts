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
    name: bytewireclients

- assert:
    that:
      - s3.name == 'bytewireclients
```

License
-------

BSD

Author Information
------------------

BGC Partners
