# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Required Protocols

### Session Workflow (BEADS.md)
Uses `bd` CLI for issue tracking.
- **Session start**: Run `bd stats` and `bd ready`
- **Session end**: Commit, push, verify `git status` shows "up to date with origin"
- Work is NOT complete until `git push` succeeds

### Architecture Principles (ZFC.md)
Follow Zero Framework Cognition when writing code:
- **DO**: Pure orchestration, IO, schema validation, policy enforcement, mechanical transforms
- **DON'T**: Local heuristics, ranking/scoring, semantic analysis, plan composition, quality judgment
- Delegate ALL reasoning to AI; build thin deterministic shells

## Repository Overview

This is a research repository for exploring and documenting ideas, experiments, and prototypes.

## Usage

Add project-specific guidance here as the repository evolves.
