# A Black-Box Privacy Analysis of Messaging Service Providers’ Chat Message Processing

This repository contains the code of the honeymessages framework used to monitor and manage the experiments conducted for `A Black-Box Privacy Analysis of Messaging Service Providers’ Chat Message Processing` (to appear at PETS 2024).

## Citation

If you use our code or refer to our results, please cite our paper.

```bibtex
@inproceedings{kirchner2024:honeymessages,
  title={A {B}lack-{B}ox {P}rivacy {A}nalysis of {M}essaging {S}ervice {P}roviders' {C}hat {M}essage {P}rocessing},
  author={Kirchner, Robin and Koch, Simon and Kamangar, Noah and Klein, David and Johns, Martin},
  booktitle={Proceedings on {P}rivacy {E}nhancing {T}echnologies ({PoPETs})},
  year={2024}
}
```

## How to use this Organization

1. **Setup the Honeymessages framework**

The central part of the paper and this organization is the [honeymessages framework](https://github.com/honeymessages/honeymessages-framework).
The repository contains the dockerized framework with a lenghty README including setup, evaluation tools, and an API sample.

2. (Optional) **Monitor App Traffic**

To extend the data caught by the framework, we instrumented mobile apps.
Follow the README instructions of the [Honeymessages AppAnalyzer Plugin](https://github.com/honeymessages/honeymessages-appanalyzer-plugin) which is a plugin to [AppAnalyzer](https://github.com/simkoc/scala-appanalyzer).

## Requirements

- Docker
- docker-compose

(Optional) To instrument mobile apps, please install the requirements for the [AppAnalyzer](https://github.com/simkoc/scala-appanalyzer) and built our [plugin](https://github.com/honeymessages/honeymessages-appanalyzer-plugin) before placing it in the `plugins` folder of the AppAnalyzer.
