# tafqeet

Write numbers and money amounts as Arabic words, for invoices, receipts and cheques:

```
1250.50 EGP  →  فقط ألف ومائتان وخمسون جنيهًا وخمسون قرشًا لا غير
```

> Status: early development.

## Planned features

- [ ] Integers to Arabic words (up to billions)
- [ ] Correct grammar for number and noun agreement (masculine/feminine, singular/dual/plural)
- [ ] Currencies: EGP, SAR, AED, KWD, USD, with their sub-units
- [ ] Invoice format ("فقط ... لا غير")
- [ ] Ordinal numbers (الأول، الثاني...)
- [ ] Gregorian to Hijri date conversion
- [ ] Command-line tool and Python API
- [ ] Large automated test suite of known correct outputs

## Planned usage

```bash
tafqeet 1250.50 --currency EGP
```

```python
from tafqeet import amount_to_words

amount_to_words(1250.50, "EGP")
```

## Roadmap

1. Project setup: packaging, CLI, tests, CI
2. Integers to words
3. Grammar rules
4. Currencies and sub-units
5. Invoice format
6. Ordinals
7. Hijri dates
8. Docs and PyPI release

## License

MIT, see [LICENSE](LICENSE).

---
Built by [Hesham Ashraf](https://www.linkedin.com/in/hesham-ashrf)
