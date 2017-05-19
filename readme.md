# Steve's SBT wrapper

A python script that wraps some commands from SBT to make them a bit easier.

## Install

It is assumed your system has python available on the command line.

First (if you haven't done so) install PIP: `curl https://bootstrap.pypa.io/get-pip.py | python`

Then download and set up this repository:

```
$ git clone git@github.com:elkdanger/ssbt
$ cd ssbt
$ pip install -r requirements.txt
$ chmod +x ssbt
```

To make the tool easier to use from anywhere, link the app to a local folder available on your path:

```
$ ln -s $(pwd)/ssbt /usr/local/bin
```

## Available commands

`$ ssbt test`

Runs tests

`$ ssbt test-only specs.*`

Runs only the specified tests

