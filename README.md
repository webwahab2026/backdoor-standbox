## Sandbox Configuration

- 7 roles
    - **target**
    - **next-target**
    - **c2-server**
    - **c2-service**
    - **c2-listner**
    - **lateral-movement**
    - **ssh_access**

- **Target** 
    - Add host aliase -- Url/hostnames 
    - Add user and set password -- fix
    - Copy Payloads 
    - Create Payload
    - Package to install -- this can depend on the narrative
    - Flag placing multiple tasks -- depend on the narrtive path dest + name of file + content if a flage to be placed 
    - Persitent inventory dest path + name + name of the process + interval 
    - **c2-listner**
        - install ncat package
        - listen  porte number + content of file to send + listen log
    - **lateral movement**
        - Script thqt continussly tranfert payload from target to next-target -- the name of the process
- **c2-server**
    - Add user name -- fix
    - Add host alias -- not sure if I need modify this
    - **c2-service**
          - Install netcat package 
          - Persistent script that connect to target and to exfilration  -- Porte + Connect message + script + path + time 

- **Next-target**
    - Add host aliases
    - Add user and set password
    - Reset the password 
    - Flag placing


         
