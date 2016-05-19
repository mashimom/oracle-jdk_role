# Docker

Role to install Oracle JDK on an Ubuntu box

##Role Variables

 * `JDK_VERSION` - the JDK version to be installed, defaults to `8`.
 * `JDK_AS_DEFAULT` - whether the alternatives should be set to this JDK as default.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
        - { role: oracle-jdk, JDK_VERSION=7, JDK_AS_DEFAULT=false}
        - { role: oracle-jdk, JDK_VERSION=8, JDK_AS_DEFAULT=true}

## License

MIT

## Author Information

Marco Shimomoto
