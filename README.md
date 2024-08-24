# LocalQuantChat

# LocalQuantChat: A Solution For Locally Deploying Financial LLMs
[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-360/)
[![PyPI](https://img.shields.io/pypi/v/alphaagent.svg)](https://pypi.org/project/alphaagent/)
![License](https://img.shields.io/github/license/LLMQuant/alphaagent.svg?color=brightgreen)
![](https://img.shields.io/github/issues-raw/LLMQuant/alphaagent?label=Issues)
![](https://img.shields.io/github/issues-closed-raw/LLMQuant/alphaagent?label=Closed+Issues)
![](https://img.shields.io/github/issues-pr-raw/LLMQuant/alphaagent?label=Open+PRs)
![](https://img.shields.io/github/issues-pr-closed-raw/LLMQuant/alphaagent?label=Closed+PRs)

<div align="center">
<img align="center" width="40%" alt="image" src="https://github.com/LLMQuant/AlphaAgent/blob/main/AlphaAgent.png">
</div>

## LocalQuantChat Overview

LocalQuantChat is a repository primarily designed for deploying large models locally and running them efficiently. It leverages SFT and RLHF to fine-tune these models with financial data. This approach not only enhances the performance of the models but also ensures the security and privacy of customers' data.


## Very first steps

### Initialize your code

1. Initialize `git` inside your repo:

```bash
cd alphaagent && git init
```

2. If you don't have `Poetry` installed run:

```bash
make poetry-download
```

> This installs Poetry as a [standalone application][fs1]. If you prefer, install it through your distribution's package manager.

3. Initialize Poetry and install `pre-commit` hooks:

```bash
make install
make pre-commit-install
```

4. Run the codestyle:

```bash
make codestyle
```

5. Upload initial code to GitHub:

```bash
git add .
git commit -m ":tada: Initial commit"
git branch -M main
git remote add origin https://github.com/llmquant/alphaagent.git
git push -u origin main
```

## License

This project is licensed under the Apache-2.0 License. See the LICENSE file for more details.

---

**Disclaimer**: The information provided in this repository is for educational purposes only and should not be construed as financial advice. Always consult with a qualified financial advisor before making any investment decisions.
