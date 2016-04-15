# Role Name: ceph-osd

A Ansible Role for ceph osd configure.

## Requirements

None.

## Role Variables

### `defaults/main.yml`.

* `ceph_cluster_name: "ceph"`
* `ceph_cluster_uuid: "80605375-25ef-46b0-afee-97aff959463f"`
* `ceph_osd_only: False`

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Install ceph osd.
      hosts: ceph-osd
      roles:
        - role: ansible-role-ceph-osd

## Author Information

z.
