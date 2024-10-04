# starter-kit
Python Project Starter Kit for Researchers

Paper: https://arxiv.org/abs/xxxx.xxxxx

<img src="https://github.com/CyberAgentAILab/starter-kit/assets/7288735/58a2eb16-734c-47ed-8d93-604699ecc9bd" alt="Cover Image">

## Prerequisites

| Software           | Install (Mac)             |
|--------------------|---------------------------|
| Python >=3.8,<3.12 | -                         |
| Docker             | -                         |
| [Poetry]           | `brew install poetry`     |
| [pre-commit]       | `brew install pre-commit` |

## Usage

```shell
poetry run python -m skit --help
````

## Installation

### Package Managers

```shell
pip install git+https://github.com/CyberAgentAILab/starter-kit.git
```

### From Source

```shell
git clone https://github.com/CyberAgentAILab/starter-kit.git
poetry install --with dev
```

## Citation

```bibtex
@inproceedings{xxx,
  title={xxx},
  author={xxx},
  booktitle={xxx},
  year={xxx},
  url={https://github.com/CyberAgentAILab/xxx.git}
}
```

## License

This project is licensed under the [MIT License](LICENSE).

[poetry]: https://python-poetry.org/
[pre-commit]: https://pre-commit.com/
