# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0] - 2025-02-18

### Fixed

- all containers now have specific versions
- ollama container is a custom build due to a open bug in the nvidia container release pipeline

### Change

- change frontend to streamlit
- change embedding models
- architecture change: remove of websockets

### Added

- setup tools


## [1.1.1] - 2024-10-31

- Fix Session 4: fix wrong paramter in huggingface call
- Fix devcontainer: fix no connection to host network
- Update add curl example as bash check in session 1 instructions

## [1.1.0] - 2024-10-20

- Update prerequisites for jetson installation
- Update workshop tasks
- Change LLM to llama3.2
- Update chatbot app
    - embedding model integrated into docker image
    - refine docker compose config


## [1.0.0] - 2024-09-16

- Initial version of workshop content