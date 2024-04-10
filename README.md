# oogway ai

> get profound knowledged from master oogway 😔

![oogway](./assets/headshot.jpg)

## Run

`OPENAI_API_KEY=<API_KEY> c r --bin cli`

<!--- [![Watch the video](./assets/demo_thumbnail.png)](./assets/demo.mp4) -->

https://github.com/cs50victor/oogway_ai/assets/52110451/9eaf199d-bffc-449e-a3fa-33e23a66ed33


## develop / publish python package

- `maturin develop -m py/Cargo.toml`
- increment version in py/Cargo.toml
- create a GitHub release with the same semver version

## develop / publish javascript package

- for new minor releaseses - `cd js && npm version patch`
- `git add .`
- `git commit -m "<version number>"`
- `git push`
