# Semver.c ESP IDF Component

Semantic version v2.0 parser and render written in ANSI C with zero dependencies.

Source code https://github.com/h2non/semver.c

## Install 

1. Add **semver** dependency to **idf_component.yml**
```yml
dependencies:
  espressif/led_strip: "*"
  idf:
    version: ">=5"
  semver:
    path: .
    git: ssh://git@github.com/stan-kondrat/semver-esp-component.git
```

2. Reconfigure project
```sh
idf.py reconfigure
```

## Usage examples

https://github.com/h2non/semver.c#usage

## License

MIT
