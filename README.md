<!-- PROJECT LOGO -->
<br />
<p align="center">
 <a href="https://github.com/nereasastre/MTL_P52">
    <img src="pitch.png" alt="Logo" height="200px">
  </a>
  <h3 align="center">Sign Language Gloss Translation</h3>

  <p align="center">
    Degree Final Dissertation 2021-2022 Automatic Sign Language Gloss Translation using Deep Learning Models
  </p>
</p>


<!-- About the project -->

## 😎 About

Sign language are communication system using gestures that are interpreted
visually. Many people in the worldwide deaf and hard of hearing communities
use sign languages as their primary means of communication. The deaf society
of the world needs to have access to all the information just like hearing people
do. For this aim, there should be a mode of direct communication between
hearing and deaf people.

In this thesis, we present a Neural Machine Translation (NMT) model system to
translate gloss german sign language text to an equivalent german text
language, and vice-versa. In order to propose an effective system, we experimented with different
encoder-decoder topologies using several neural architectures (Transformers
and Long short-term memory (LSTM)). We then find a data-driven mapping
between glosses and the equivalent sentence language in other domains.
The different approaches are evaluated on a recently released german glosses
sign language translation dataset. In the experiments reported here, we
compare the different settings based on the BLEU-4 score to guide the model
and model tuning.

The outcomes of this research are expected to contribute to reducing the
communication barriers between both parties.

## 👉🏽 Getting Started

### Prerequisites

Make sure to install

- [Python 3.10.5](https://www.python.org/downloads/)
- [Pip](https://pip.pypa.io/en/stable/installation/)

### Installation

1. Clone the repo

```sh
git clone https://github.com/APPIAHTECH/NMT
```

2. You need  Jupyter or Google Colab to run the code

[Google](https://colab.research.google.com/?utm_source=scs-index)<br>
[Jupyter](https://jupyter.org/)

<!-- CONTRIBUTING -->
## Contributing

Contributions are what makes the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Keras Transformers English-to-Spanish translation with a sequence-to-sequence Transformer](https://keras.io/examples/nlp/neural_machine_translation_with_transformer/)<br>
* [Keras LSTM/RNN A ten-minute introduction to sequence-to-sequence learning in Keras](https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html)