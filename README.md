# serverless.env.yml Parser

## Description

A package to extract environmental variables from serverless.env.yml for local development.

## Installation

```
pip install serverless-env-yml-parser
```

## Usage

```
if os.environ['STAGE'] == 'LOCAL':
    from sls_env_yml_parser import yml_parser
    yml_parser.parse_env_yml("serverless.env.yml")
```

## Where to get it

The source code is currently hosted on GitHub at:
https://github.com/e-ndrus/sls-env-yml-parser


## License

[MIT][mit]


## Contributions

All contributions, bug reports, bug fixes, documentation improvements, enhancements and ideas are welcome.

Issues are posted on:
https://github.com/e-ndrus/sls-env-yml-parser/issues


[pcking]: https://packaging.python.org
[mit]: https://github.com/e-ndrus/sls-env-yml-parser/LICENSE.txt