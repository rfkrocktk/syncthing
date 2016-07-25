# Syncthing SELinux Support

## Types

<dl>
    <dt>user_home_dir_t</dt>
    <dd>The actual user's home dir, ie <code>/home/user/</code></dd>
    <dt>user_home_t</dt>
    <dd>Files and directories in a user's home directory, ie <code>/home/user/* </code></dd>
    <dt>config_home_t</dt>
    <dd>User configuration files, ie <code>/home/user/.config(/.\*)?</code></dd>
</dl>
