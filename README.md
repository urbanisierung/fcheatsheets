# `Fabulous cheatsheets`

![GitHub repo size](https://img.shields.io/github/repo-size/urbanisierung/fcheatsheets)
![GitHub contributors](https://img.shields.io/github/contributors/urbanisierung/fcheatsheets)
![GitHub stars](https://img.shields.io/github/stars/urbanisierung/fcheatsheets?style=social)
![GitHub forks](https://img.shields.io/github/forks/urbanisierung/fcheatsheets?style=social)
![Twitter Follow](https://img.shields.io/twitter/follow/urbanisierung?style=social)

`fcheatsheets` is a repository for cheatsheets that can be used in [`fcheats`](https://github.com/urbanisierung/fcheat)

## Using `fcheatsheets`

The default directory for cheatsheets from `fcheat` is `~/.config/fcheat`. Change to this directory and clone this repository.

```bash
cd ~/.config/fcheat # or your preferred directory
git clone https://github.com/urbanisierung/fcheatsheets
```

### Adding further cheatsheets

The format is very simple:

```json
[
    {
        "title": "some explanation",
        "command": "command -example",
        "tags": [ "tags", "are", "optional" ]
    }
]
```

For simplicity, the files have the extension `cheat.json`.

## Contributing to `fcheatsheet`

I would be very happy if more cheatsheets are contributed.

## Contact

If you want to contact me you can reach me at [adam.urban@gmail.com](mailto:adamurban@gmail.com).

## License

This project uses the following license: [MIT](./MIT.md).
