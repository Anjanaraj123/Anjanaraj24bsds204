 SERVER MANAGEMENT FOR CACHE MANAGER
- cache manager is a system or software component to managing the storage,retrival and 
efficient of cache data in computing 
- cache is a technique used to temporary storage of the frequently accessed data
 
PURPOSE
- It will improve the performance and reduce latency

EXAMPLES:
- Redis
   Its is a open source 
   in-memory data store that can be used as cache memory
- Memcache
   It is used to speeding up the dynamic web application by caching data

BENEFITS:
- Improved performance
- Reduced latency
- Reduced load on Backend systems

TYPES OF CACHE MANAGER:
- Local cache manager
- Distributed cache manager
- Hydrid cache manager
- Persistence cache manager

HOW IT WORKS:
- Development od cache manager
- Configuration
- Scaling
- Monitoring


COMMANDS USED:
- First you create a new directory in your directory using the command
    mkdir cache_data
    ls
   check its is created or not using ls command 
- Next you create a subdirectory in that current directory using the command 
    mkdir January February ....
    ls 
- Rename and move the file using the command
     touch cachehitlogs1 ......
     cd January
     ls
     mv ./January/cachehitlogs February
     ls
-Navigating and listing files
     cd ..
     cd cache_data
     ls 
Permission file management:
     create file as  "cache_config.txt" using the command 
         touch cache_config.txt
         cd cache_config.txt
     changing permission
           chmod 744 cache_config.txt
     checking
         ls -l
Network checking 
    ping google.com
to check history
    history
File sorting 
     sort cache_data
