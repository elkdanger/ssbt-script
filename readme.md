# Steve's SBT wrapper

A python script that wraps some commands from SBT to make them a bit easier.

## Install

It is assumed your system has python and pip available on the command line.

```
$ git clone git@github.com:elkdanger/ssbt
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

