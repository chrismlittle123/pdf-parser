## PDF Parser

Parses PDF files and extracts text, tables and other data. Uses templates, with a template identifier built in. Aims to mimic the functionality of AWS Textract.

Bugs:

- Barclays:
  - Use statement date year is not working

Start up:

python -m venv venv
source venv/bin/activate
pip install -r requirements_dev.txt



Checks:

pre-commit run --all-files

mypy {path_to_file_or_directory} --explicit-package-bases


Generate types:

npm run generate-types
