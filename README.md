# project
    - hosts: servers
      vars:
        curl_pkg_state_latest: yes
      roles:
         - { role: shrikeh.curl }
