mgt_gcp_iam
=========

This role it's the first bricks of our GCP user management tools. The purpose of this Ansible it's to help use to industrialize the serviceAccount life cycle.

Requirements
------------

Ansible > 2.4
Gcloud 258.0.0

Role Variables
--------------

* service_name: service_name
* display_name: Display name of the service account
* project_name: Project name
* path_to_auth: Path for generated meta data file for the service account
* state: The state could be present,modify,view or delete

Dependencies
------------

No Dependencies

Example Playbook
----------------

An example of playbook to simplify the service creation

    - hosts: servers
      roles:
         - { role: mgt_gcp_iam }

License
-------

BSD

Author Information
------------------

Passionate by building performance in the Technologies services
