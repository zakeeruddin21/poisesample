# poisesample-cookbook

TODO: Enter the cookbook description here.
The poise cookbook is a set of libraries for writing reusable cookbooks.  Read more: https://github.com/poise/poise

## Supported Platforms

TODO: List your supported platforms.

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['poisesample']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### poisesample::default

Include `poisesample` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[poisesample::default]"
  ]
}
```

## License and Authors

Author:: YOUR_NAME (<YOUR_EMAIL>)
