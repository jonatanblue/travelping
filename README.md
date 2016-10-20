# Travelping

On a train, over 4G, connection drops in and out, I want to know:

**How bad is my connection?**

Travelping pings a well known server every 5 seconds and reports the time (or timeout).

## Install

    cd ~/bin
    curl -O https://raw.githubusercontent.com/jonatanblue/travelping/master/travelping
    chmod +x travelping


## Usage

    $ travelping
    time=22.216 ms
    time=15.983 ms
    time=14.186 ms
    time=16.080 ms
    time=13.095 ms
    ...

