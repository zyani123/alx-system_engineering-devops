# Configuration management

### Resources:

1. [Intro to Configuration Management](https://www.digitalocean.com/community/tutorials/an-introduction-to-configuration-management)
2. [puppet-lint](http://puppet-lint.com/)
3. [Puppet emacs mode](https://github.com/voxpupuli/puppet-mode)
4. [Puppet docs](https://puppet.com/docs/puppet/3.8/index.html)

### Installing `puppet-lint`

```
$ apt-get install -y ruby
$ gem install puppet-lint -v 2.1.1
```

### Running a manifest

```
puppet apply some_file.pp
```

### Using puppet-lint

```
puppet-lint some_file.pp

```


