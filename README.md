# Franx General Public License (FGPL)

**Version 0.9, 9 May 2026**

The Franx General Public License is a free, copyleft license that extends the protections of the GNU Affero General Public License to address the challenge of artificial intelligence training.

## Why FGPL?

The AGPLv3 closed the "SaaS loophole" in the GPLv3. But a new loophole has emerged: the output of free software can be collected and used to train proprietary machine learning models, with the community receiving neither the model architecture, nor the training code, nor the trained weights in return.

FGPL closes this "AI training loophole." If you use FGPL-licensed software or its derivative works to train an AI model and share that model with others, you must release the model under the same copyleft terms.

## What FGPL Requires

- **If you use the software privately**, including private AI training: **no obligations**.
- **If you share a model** trained on FGPL-licensed software (or its derivative works) with any third party: you must provide the **Corresponding Model Information** and **Corresponding Weights** under the same license.

**Corresponding Model Information** includes:
- Model architecture
- Training and inference code
- Hyperparameter configurations
- **The training data and related scripts used to process that data**
- Any other information necessary to reproduce or modify the model

**Corresponding Weights** means the trained parameter files of the model.

## Compatibility

FGPL v0.9 is designed to work with:

- GNU General Public License v3 (or any later version)
- GNU Affero General Public License v3 (or any later version)
- Franx General Public License v0.9 (or any later version)

> *Note: This compatibility statement is based on the text of FGPL v0.9 and the licenses named. It has not been formally reviewed by the Free Software Foundation, but follows the same structural approach as GPL/AGPL compatibility. This is a draft version (0.9). The final v1.0 will be released after legal review.*

## How to Use FGPL for Your Project

1. Copy the `COPYING` file (the full license text) into your project root.
2. Add the following notice to each source file (replace `<year>` and `<name of author>`):

```
Copyright (C) <year> <name of author>

This program is free software: you can redistribute it and/or modify
it under the terms of the Franx General Public License, either version 0.9
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
Franx General Public License for more details.

You should have received a copy of the Franx General Public License
along with this program.  If not, see <https://github.com/xhdlphzr/FGPL>.
```

## Frequently Asked Questions

### Can I use FGPL-licensed software for private AI training?  
Yes. FGPL only requires you to open your model when you **share it with others**. Private use (including internal research, personal projects, or even training a model that you never distribute) is completely unrestricted.

### Is FGPL compatible with the GPL and AGPL?  
FGPL v0.9 is compatible with GPLv3-or-later and AGPLv3-or-later for creating combined works. Each part retains its own license. This is the same definition of compatibility used by the FSF.

### Does FGPL restrict Freedom 0 (the freedom to run the program for any purpose)?  
No. You may run FGPL-licensed software for any purpose, including AI training, without triggering any obligations. The obligations arise only when you **share** a model trained on the software.

### Can I modify the FGPL text itself to create my own license?  
Yes, **but** with restrictions. You may modify the FGPL text to produce a derived license, provided that:
- You remove the name "Franx" and the original preamble.
- You clearly mark your version as a modified version, not the original FGPL.
- You do not use the name "xhdlphzr" or imply endorsement by the original author.

This is similar to how the GNU GPL family allows modification of their license documents (with removal of the original preamble and names).

### Why can’t I just change the license text and still call it "FGPL"?  
To avoid confusion. The name "Franx General Public License" and the original text are the author’s mark. Changed versions must be clearly distinguished so that users know which obligations apply.

### Where can I get legal advice about using FGPL?  
You are encouraged to consult a lawyer familiar with free software licenses. For general questions, you can open an issue on the FGPL GitHub repository or contact the author (see below). Software Freedom Law Center may also provide guidance in some cases, but they do not represent you unless explicitly engaged.

### Where can I find the full license text?  
The full legal text of FGPL v0.9 is in the `COPYING` file in this repository. It is also available at <https://github.com/xhdlphzr/FGPL/blob/main/COPYING>.

## License of this README and the FGPL text

- The **FGPL license text** (the `COPYING` file) is copyrighted by xhdlphzr. Everyone is permitted to copy and distribute verbatim copies of this license document, but changing it is not allowed unless you follow the modification rules described in the FAQ above.
- This `README.md` file is released under the same terms as the FGPL itself, or under CC0 1.0 Universal (public domain) – at your option. For simplicity, you may treat it as part of the FGPL documentation.

## Contact

For questions, suggestions, or feedback:  
**xhdlphzr@outlook.com** (preferred)  
GitHub: [xhdlphzr/FGPL](https://github.com/xhdlphzr/FGPL)

---

*"When you benefit from freedom, and you choose to share that benefit with others, you must pass the same freedom along. It is not a restriction on what you can do in private. It is a promise you make to the community at the moment you decide to give something to the world."*  
— xhdlphzr