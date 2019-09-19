# chef_nagios3 Cookbook

This cookbook configures your Nagios 3 server

## Requirements

### Platforms

- Linux

### Chef

- Chef 12.0 or later

### Cookbooks

## Attributes

## Usage

### chef_nagios3::default

Just include `chef_nagios3` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[chef_nagios3]"
  ]
}
```

## Contributing

e.g.
1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

## License and Authors

Authors: adam.salowitz+github@gmail.com

License: [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/legalcode)

