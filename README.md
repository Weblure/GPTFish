<div align="center">
  <a href="https://fishtailprotocol.com/projects/GPTFish/" title="Visit Project Webpage"><img src="https://img.shields.io/badge/status-Early_Concept-orange" alt="Project Status"></a>
  <a href="https://github.com/Weblure/GPTfish/pulls" title="Open Pull Requests"><img src="https://img.shields.io/badge/contributions-welcome-brightgreen" alt="Contributions Welcome"></a>
  <a href="https://github.com/Weblure/GPTfish/issues" title="Open Issues"><img src="https://img.shields.io/github/issues/Weblure/GPTfish" alt="Open Issues"></a>
  <a href="https://github.com/Weblure/GPTfish/pulls" title="Open Pull Requests"><img src="https://img.shields.io/github/issues-pr/Weblure/GPTfish" alt="Open Pull Requests"></a>
  <br>
  <a href="https://tesseract.projectnaptha.com/" title="Tesseract - Project Naptha"><img src="https://img.shields.io/badge/dependencies-Tesseract.js-orange" alt="Tesseract.js"></a>
  <a href="https://openai.com/" title="OpenAI"><img src="https://img.shields.io/badge/dependencies-GPT--3.5--turbo-blue" alt="GPT-3.5-turbo"></a>
  <br>
  <a href="https://www.gnu.org/licenses/gpl-3.0.en.html" title="License"><img src="https://img.shields.io/badge/license-GPLv3-blue" alt="License"></a>
</div>

# GPTfish

GPTfish is an early work-in-progress project that aims to provide a web-based solution for translating comics into English. It utilizes OCR (Optical Character Recognition) and the GPT-3.5-turbo language model from OpenAI to extract text from comic panels, translate it, and overlay the translated text onto the original image.

## (Planned) Features

- Drag-and-drop interface for uploading comic images.
- OCR text extraction to extract text from each panel of the comic.
- Integration with the GPT-3.5-turbo API for translation of extracted text.
- Typesetting of translated text onto a user-supplied 'blank' of the original image.
- Download functionality to save the modified image with translated text.

## Project Status

GPTfish is currently in the early stages of development. It is not yet ~~feature-complete~~ functional and ~~may have limited functionality~~ has no functionality. ~~Contributions and feedback are welcome!~~ (This shouldn't even be public yet lol)

## Installation and Usage

GPTfish is entirely web-based. Almost all functionality is ran locally in the browser, though some features (such as GPT tokenization) relies on PHP.

## Dependencies

- Tesseract.js: A JavaScript OCR library for text extraction from images.
- GPT-3.5-turbo API: OpenAI's language model for translation.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [GNU General Public License (GPL)](LICENSE).

## Disclaimer

GPTfish is an independent project and is not affiliated with or endorsed by OpenAI.
