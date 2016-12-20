# Ansible Role: Scrapy

Installs Scrapy on Centos 7

## Requirements

Tested CentOS 7

## Role Variables

List of yum packages scrapy needs.

```
scrapy_dependencies:
  - python
  - python-pip
  - python-devel
  - gcc
  - libxml2
  - libxml2-devel
  - libxslt
  - libxslt-devel
  - openssl
  - openssl-devel
  - libffi
  - libffi-devel
```

Install scrapy on python virtual environment.

```
scrapy_in_virtualenv: false
```

The virtual environment namespace.

```
scrapy_virtualenv: /my_app/venv
```

Extra pip libraries.

```
scrapy_extra_libraries:
  - ScrapyElasticSearch
```

## Dependencies

None

## License

MIT

## Author Information

Apostolos Tovletoglou [ansible-role-scrapy](https://github.com/tovletoglou/ansible-role-scrapy)
