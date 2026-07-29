# Changelog

All notable changes to Raisin will be documented here.

# Changelog

## v0.2

### Changed

- Confidence is now treated as a first-class concept during reasoning.
- Decision-changing assumptions should be supported by the smallest credible artifact when practical.
- Sessions conclude with a final challenge question before recommending implementation.

### Why

These changes resulted from a real Thrift→gRPC migration planning session.

Red-team review showed several load-bearing assumptions were accepted through conversation alone, reducing confidence in the resulting plan.

The methodology now encourages strengthening confidence in decision-changing claims before convergence.

## [0.1.0-alpha] - Unreleased

### Added

- Conversational Raisin guidance for AI-assisted technical-change planning
- Agent maturity guidance and lightweight pilot records
- Entry guidance for Codex, Cursor, and Claude workflows
