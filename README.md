# Role Name

<!-- A brief description of the role goes here. -->
This role deploys HTCondor CE.

## Requirements

<!--
Any pre-requisites that may not be covered by Ansible itself or the role should be
mentioned here.
For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.
-->
Requirements are listed in `requirements.yml` file.

## Role Variables

<!--
A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.
-->

## Dependencies

<!--
A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Use https://galaxy.ansible.com/EGI-Foundation/ roles first if possible.
-->
The role installs HTCondor CE from the EGI repositories. Consequently, they need to be available in the system before actually installing the product. Similarly, since HTCondor CE depends on the previous deployment of HTCondor, the `ansible-role-htcondor` is required.


## Example Playbook

<!--
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too.
Be sure to write the dependencies explicitly.

```yaml
    - hosts: servers
      roles:
         - { role: EGI-Foundation.dependency1 }
         - { role: EGI-Foundation., x: 42 }
```
-->

## License

Apache-2.0

## Author Information

<!--
Add the relevant contributors
-->
Check `AUTHORS.md`.
