# Multi Docker Compose

Stupidly simple CLI tool that makes working with multiple compose files on 
regular basis a bit less tiresome.

## Installation

TODO ;)

## Usage

When set up, instead of repeating:

```shell script
docker-compose -f docker-compose.yaml -f docker-compose.local.yaml <command>
```

You can do:

```shell script
mdcompose <command>
```

## Settings

For mdcompose to know which compose files to use, you need a `.mdcompose`  file
within the folder, e.g.:

Example `.mdcompose`
```
docker-compose.yaml
docker-compose.local.yaml
docker-compose.personal.yaml
```

You can generate the file by using `mdcompose init <file1> <file2>`

More options to come soon!
