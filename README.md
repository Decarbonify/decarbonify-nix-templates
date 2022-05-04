# Nix Templates and utilities for Decarbonify

This contains nix utillities used across many projects by Yatima Inc.

## Templates

To use a template, for example the lean package template, run `nix flake template -t github:decarbonify/decarbonify-nix-templates#leanTemplate`.

| Template name       | Description                                                                        |
|---------------------|------------------------------------------------------------------------------------|
| rustLibTemplate     | A basic flake build template using naersk. Remember to add `Cargo.lock` to git.    |
| leanTemplate        | A simple setup for a lean package.                                                 |
| cLibTemplate        | A minimal setup for building C/C++ libraries.                                      |
| nixGithubCI         | A github action template for nix flakes. Usually not necessary to change anything. |
