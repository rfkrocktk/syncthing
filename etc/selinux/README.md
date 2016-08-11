# Syncthing SELinux Support

Requirements:

 - userdom_basic_networking(syncthing_t) - allow connecting to tcp/udp sockets
 - userdom_user_home_content(syncthing_config_t) - mark type as user home content
 - userdom_user_application_domain(syncthing_t, syncthing_exec_t) - mark as domain
 - userdom_manage_user_home_content(syncthing_t) - manage all user files
