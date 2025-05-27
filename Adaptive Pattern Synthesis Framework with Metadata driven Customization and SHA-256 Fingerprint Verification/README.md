# Thematic Styling & Cryptographic Fingerprinting for Original Software Artifacts

## Description
This Java-based program is a novel and modular pattern generation engine that empowers users to create visually artistic outputs with configurable themes and cryptographically verifiable originality. It integrates a lightweight DSL-style configuration, multi-pattern rendering, and SHA-256 fingerprinting to ensure every result is traceable and copyright-defendable.

## Novelty:

- Implements a self-contained artistic engine with clean separation of concerns.

- Uses DSL-like pattern metadata parsing, rare in visual console applications.

- Includes SHA-256 cryptographic fingerprinting for authorship proof.

- Designed with modularity, supporting scalable pattern types and themed output.

The architecture is domain-adaptable: console UI today, GUI or web in the future.

##  Key Features
- Thematic Character Styling: Supports characters like +, @, #, * to generate emotion-based visual patterns.

- DSL-Based Configuration: Accepts structured multi-line inputs like:


pattern: diamond
theme: plus
size: 7
emotion: joyful
license: CC-BY-SA-4.0
version: 1.2

- Multiple Pattern Types: Includes Triangle, Diamond, and Hourglass generators.

- Metadata Embedding: Captures version, license, timestamp, emotion, and more.

- SHA-256 Fingerprint Output: Generates a secure digital fingerprint to uniquely identify the pattern and its metadata.

- Extensible Design: Supports seamless addition of new themes or shapes.

## Author: Panchadip Bhattacharjee, Advithiya Duddu

## License: Customizable in DSL (default: CC-BY-SA-4.0 or MIT)

## Protection: Each pattern and metadata set is signed using SHA-256, providing a tamper-proof proof of origin.

