===============
Ubuntu geoclue2
===============

## Prereqs
   
   apt install g++ cmake libdbus-1-dev libdbus-cpp-dev libproperties-cpp-dev libboost-system-dev
   
## Build

```sh
mkdir build
cd build

cmake ..
make
```

## Notes
Running `./build/ubuntu-location-provider-geoclue2` results in

> terminate called after throwing an instance of 'std::runtime_error'
  what():  org.freedesktop.DBus.Error.AccessDenied: Connection ":" is not allowed to own the service "com.wolfpack.geoclue2.Service.Provider" due to security policies in the configuration file

