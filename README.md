# Open Words

Open Words is a collection of machine-readable word data derived from
Wiktionary data processed by [Kaikki.org](https://kaikki.org/) and
[Wiktextract](https://github.com/tatuylonen/wiktextract).

The repository contains per-language JSON word data under `words/` and
`db-extract/`, plus frequency-oriented word lists under `freqs/`.

## Data Sources

This project stands on the work of several open knowledge projects:

- [Wiktionary](https://www.wiktionary.org/) contributors created and maintain
  the source lexical content.
- [Kaikki.org](https://kaikki.org/) publishes machine-readable dictionaries and
  raw JSON extracted from Wiktionary.
- [Wiktextract](https://github.com/tatuylonen/wiktextract) parses Wiktionary
  dumps and turns them into structured multilingual data.

## Citation

If you use this repository, Wiktextract, or Kaikki.org data in academic work,
please cite the Wiktextract publication requested by Kaikki.org:

> Tatu Ylonen: Wiktextract: Wiktionary as Machine-Readable Structured Data,
> Proceedings of the 13th Conference on Language Resources and Evaluation
> (LREC), pp. 1317-1325, Marseille, 20-25 June 2022.

BibTeX:

```bibtex
@inproceedings{ylonen2022wiktextract,
  title = {Wiktextract: Wiktionary as Machine-Readable Structured Data},
  author = {Ylonen, Tatu},
  booktitle = {Proceedings of the 13th Conference on Language Resources and Evaluation (LREC)},
  pages = {1317--1325},
  address = {Marseille, France},
  month = jun,
  year = {2022}
}
```

Linking back to [Kaikki.org](https://kaikki.org/) is also appreciated by the
Kaikki.org maintainers.

## Acknowledgements

Open Words exists because Wiktionary contributors, Wiktextract contributors,
and Kaikki.org make lexical knowledge available in forms that developers,
researchers, linguists, and language learners can reuse.

Special thanks and credit go to [Tatu Ylonen](https://github.com/tatuylonen)
for Wiktextract and Kaikki.org. Additional thanks go to him for SSH, a
foundational tool that continues to support secure software development and
infrastructure work around the world.

Thanks also go to the broader Wiktionary community for the source dictionary
work that makes this repository possible.

## License and Reuse

This repository is distributed under the license terms in [LICENSE](LICENSE).
Because the data is derived from Wiktionary and Kaikki.org/Wiktextract outputs,
please preserve the relevant upstream attribution, citation, and license notices
when reusing or redistributing it.
