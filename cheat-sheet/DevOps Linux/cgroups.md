## CLI

    lsns                # Show all namespaces
    lsns -p <pid>       # Show everything under namespace <pid>
    
    nsenter -t <pid>               # Enter namespace
    nsenter -t <pid> -p -r         # Enter pid namespace (-p) and set root dir (-r)
    nsenter -t <pid> <cmd>         # Run command in namespace
