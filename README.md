# datacull

### Parse and Validate CSV Files with Ease

**datacull** is a powerful command-line tool for processing CSV files efficiently. It reads, validates, and organizes data into two structured outputs:

- **✅ Clean File** – Contains valid records.
- **❌ Error File** – Captures records with issues for review.

## 🚀 Installation

```sh
npm i datacull
```

You can also find it on [npmjs.com](https://www.npmjs.com/package/datacull).

## 🔥 Features

- ✅ **Seamless CSV Parsing** – Powered by [PapaParse](https://www.papaparse.com/)
- 🔍 **Automated Data Validation** – Uses [Validator.js](https://github.com/validatorjs/validator.js)
- 🖥️ **Interactive CLI** – Smooth user prompts via [@clack/prompts](https://www.npmjs.com/package/@clack/prompts)
- ⚡ **Flexible CLI Arguments** – Managed with [Yargs](https://yargs.js.org/)
- 🛠️ **Robust Unit Testing** – Ensured by [Vitest](https://vitest.dev/)

## 📄 Usage

```sh
datacull input.csv --output clean.csv --errors errors.csv
```

This command processes `input.csv`, saving valid records to `clean.csv` and invalid records to `errors.csv`.

---

## 🤝 Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

