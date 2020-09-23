# k1s User Interface

This repository contains the Hugo static dashboard for the k1s platform.

## Getting Started

### Dependencies

* [Golang](https://github.com/golang/go)
* [Hugo](https://github.com/gohugoio/hugo)

### Installing

* Install from source.

    ```sh
    mkdir $HOME/k1s-ui
    cd $HOME/k1s-ui
    git clone https://github.com/gohugoio/hugo.git
    cd hugo
    go install --tags extended
    ```

### Executing the program

* Start the Hugo server for local development with drafts (`-D` flag) enabled.

    ```sh
    cd $HOME/k1s-ui
    git clone git@github.com:nushkovg/k1s-ui.git
    cd k1s-ui
    hugo server -D -v
    ```
