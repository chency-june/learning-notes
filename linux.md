## linux notes

- ssh

    Make a dir ```~/.ssh```

    Use ```ssh-keygen``` to generate the ```id_rsa``` and ```id_rsa.pub```

    - config
        ```
        Host host
            User username
            Hostname hostname
            Port port
        ```
        then, just ``` ssh host``` will work.
