# AutoGPT for Web App Development 

"Programmers have programmed themselves out of jobs" - Unknown

AutoGPT for web app development is an autonomous agent that builds ReactJS, Flask, Express, etc. applications just from prompts, following the Test-Driven Development (TDD) approach. It starts by writing tests for a feature, then implements the code to pass the tests, runs the tests and fixes any issues. 

The agent can successfuly build simple CRUD apps. The TDD approach helps to keep the agent focussed on the goal. If it gets stuck, just modify the prompt and restart.

This project is in early alpha stage. GPT-4 API key is required.

## Setup Instructions

1. Setup a virtual environment:
```
python3 -m venv env
```

2. Activate the virtual environment:
- On macOS and Linux:
  ```
  source env/bin/activate
  ```
- On Windows:
  ```
  .\env\Scripts\activate
  ```
3. Clone the repository to your local machine:
```
git clone https://github.com/gimlet-ai/dev-gpt.git

```
4. Navigate to the project directory:
```
cd dev-gpt
```

5. Run the following command to install the package and its dependencies:
```
python setup.py install
```

6. Set up your GPT-4 API keys as environment variables.
```
export OPENAI_API_KEY="sk-..."
```

7. Run dev-gpt
```
dev-gpt --prompt 'build a flask app with a form to record the name, address, dob, height and weight and store it in a sqlite db'
```

Check the flask-app directory for the generated app.

## Similar Projects

- [Aider](https://github.com/paul-gauthier/aider)
- [Smol Developer](https://github.com/smol-ai/developer)
- [GPT-Engineer](https://github.com/AntonOsika/gpt-engineer)
- [Mentat](https://github.com/biobootloader/mentat)


## Contributing

We welcome contributions to this project. Please feel free to submit issues and pull requests. For major changes, please open an issue first to discuss what you would like to change.


## License

This project is open source, under the [MIT license](LICENSE).

## Contact

If you have any questions or comments, please feel free to reach out to us on GitHub.
