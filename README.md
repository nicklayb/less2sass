# less2sass 
[![Gem Version](https://badge.fury.io/rb/less2sass@2x.png)](https://badge.fury.io/rb/less2sass)

Convert Less file to a Sass file

### Installation
    % gem install less2sass

### Usage
    % less2sass inputfile.less [options]

### Example
    % less2sass styles.less

    % less2sass styles.less -o styles.scss
both examples result in ```styles.scss```

### Options

| option          | parameter    |                              |
|---------------  |------------  |----------------------------  |
| -o, --output    | FILE.scss    | name of outputfile           |
| -d, --delete    |              | delete inputfile after outputfile is created |
| -p, --print     |              | output sass results to the terminal |
| -v, --version   |              | print less2sass version      |
| -h, --help      |              | print help                   |
