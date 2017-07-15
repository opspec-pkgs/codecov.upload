# Problem statement
uploads a coverage report to codecov.io

# Example usage

> note: in examples, VERSION represents a version of the codecov.upload pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/codecov.upload#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/codecov.upload#VERSION
```

## compose

```yaml
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/codecov.upload#VERSION }
    inputs: 
      gitBranch:
      gitCommit:
      token:
      report:
```

# Support

join us on [![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or [open an issue](https://github.com/opspec-pkgs/codecov.upload/issues)
