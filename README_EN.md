
# Graduated Open License (GOL)

An open-source license that **gradually relaxes over time**, protecting contributors' rights while ultimately releasing works into the public domain.

---

## What Is This?

**Graduated Open License (GOL)** is a progressive open-source license. Its core idea is:

> **Newly published contributions start under strong copyleft and gradually relax over time, eventually entering the public domain.**

Most open-source licenses are one-shot—either permissive (MIT) or copyleft (GPL), fixed once released. GOL attempts to provide a **middle path**:

- **Short term**: Protect contributors' works from being used in closed-source products by others
- **Medium term**: After several years, convert to a permissive license so more people can benefit
- **Long term**: Eventually enter the public domain, becoming the common heritage of all humanity

---

## License Timeline

Day 1 of each Contribution is its **first public release or submission date** (UTC). Each following UTC date increases the day number by one.

Using **GOLv1** as an example:

| Phase             | Time Point    | License Granted             | Meaning                                                                                                  |
| :---------------- | :------------ | :-------------------------- | :------------------------------------------------------------------------------------------------------- |
| **Phase 1** | From Day 1    | **CC BY-SA 4.0**      | Anyone may freely use, modify, and distribute, but derivative works must be shared under the same terms. |
| **Phase 2** | From Day 1096 | **MIT**               | In addition to CC BY-SA 4.0, the MIT License also applies, allowing use under more permissive terms.     |
| **Phase 3** | From Day 7301 | **CC0 1.0 Universal** | The work enters the public domain; anyone may use it without restriction and without attribution.        |

> Later phases do not revoke rights already granted. Once a license takes effect, recipients may continue to rely on it.

## How to Use

### Adopting GOLv1

Copy `GOLv1/LICENSE` into your project and replace `[YEAR]` and `[COPYRIGHT HOLDER]`, for example:

```
Graduated Open License, Version 1.0 (GOLv1)

Copyright (c) 2026 SunRuikang

1. CONTRIBUTIONS AND DATES ... 
```

### Adopting CGOLv1 (Custom Version)

CGOLv1 lets you customize the licenses and time points used in the three phases:

```text
First License: [full name and version]
Second License: [full name and version]
Public-Domain Instrument: [full name and version]
A: [integer greater than 1]
B: [integer greater than A]
```

---

## License

The license texts in this repository are released under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/). You may freely copy, modify, and use them. We strongly recommend that any license derived from this license use a name distinct from this one to avoid confusion among users.

---

## Contributing

GOL and CGOL are currently in their first version. They may have many shortcomings, and perhaps a v2 should eventually replace them. Contributions via Issues are welcome:

- Report problems or ambiguities in the license texts
- Suggest compatibility improvements
- Share your experience using them
