# `icp_ledger_agent`

An AI agent example to interact with ICP blockchain ledgers.

## Running locally

```sh
git clone https://github.com/ldclabs/anda-examples.git
cd anda-examples
cp example.env .env
# update .env
cargo run -p icp_ledger_agent
```

Install CLI tool and run agent:
```sh
cargo install anda_cli
anda_cli --help
anda_cli agent-run --help
anda_cli agent-run -p 'Please check my PANDA balance'
anda_cli tool-call -n icp_ledger_balance_of -a '{"account":"535yc-uxytb-gfk7h-tny7p-vjkoe-i4krp-3qmcl-uqfgr-cpgej-yqtjq-rqe","symbol":"PANDA"}'
```

## License
Copyright © 2025 [LDC Labs](https://github.com/ldclabs).

`ldclabs/anda-examples` is licensed under the MIT License. See the [MIT license][license] for the full license text.

[license]: ./../../LICENSE
