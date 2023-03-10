# Ansible Role: udf

Ansible role to manage the udf filesystem module


## Requirements

    None


## Dependencies

    None


## Role Variables

    None


## Example playbook

    ```yaml
    ---
    - hosts: all

      roles:
          - foolean/udf
    ```


## Supported Operating Systems

    * Debian (11)
    * Raspbian (11)
    * RedHat (8)
    * Rocky (8)


## Compliance

    * CIS Debian Linux 11 Benchmark v1.0.0
    * CIS RedHat Enterprise Linux 8 Benchmark v2.0.0
    * CIS Rocky Linux 8 Benchmark v1.0.0


### Deviations

    * Microsoft Azure requires the use of udf


## License

    BSD-3-Clause
