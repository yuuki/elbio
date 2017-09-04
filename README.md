elbio
=====

A CLI tool to gracefully manage instances on ELB.

```shell
$ elbio status
[
    {
        "name": "elbtest001",
        "dnsname": "elbtest001-00000000.ap-northeast-1.elb.amazonaws.com",
        "instances": [
            {
                "instance-id": "i-xxxxxxxxxxxxxxxxx"
            },
            {
                "instance-id": "i-yyyyyyyyyyyyyyyyy"
            }
        ]
    }
]
```

```shell
$ elbio detach
$ # something restart command
$ elbio attach
```

## License

[The MIT License](./LICENSE).

## Author

[yuuki](https://github.com/yuuki)
