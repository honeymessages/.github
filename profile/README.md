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

1. Setup the Honeymessages framework

The central part of the paper and this organization is the honeymessages framework. 
honeymessages-docker contains the dockerized framework with a lenghty README including setup and evaluation tools.

2. Monitor App Traffic

To augment the data caught by the framework, we instrumented mobile apps. Our setup and tools are available in this organization.


## Requirements

- Docker
- docker-compose
