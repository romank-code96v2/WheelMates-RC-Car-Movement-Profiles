# WheelMates: Feature Scope

Status: Module concept - not implemented. Checked 2026-09-05.

The items below are proposed capabilities. They are not release notes or a list of working features.

## Driving practice

Design per-section practice notes and repeatable attempts for difficult driving sequences.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Movement tuning

Investigate bounded speed and acceleration changes only after verifying how both cars synchronise.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Jump experiments

Research jump-related practice parameters where the game exposes suitable values; no parameter support is assumed.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Section profiles

Investigate whether local progress can be restored consistently for both participants.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Puzzle clues

Plan staged hints and route annotations for oversized obstacles and hidden paths.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Two-player agreement

Show each proposed shared-session change to both participants before an experimental profile is used.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Shared application architecture

This theme is one adapter for a common application. The shared interface can manage profiles and show change previews; each game adapter must implement and validate its own behaviour. No universal memory addresses, item identifiers, save paths or hotkeys are supplied.

## Session scope

Shared-session experiments require an agreed private group. Host and guest state must be tested separately; the package does not claim an offline mode or solo support for a co-op-only game.

## First implementation target

Two friends want to repeat a difficult obstacle. A proposed practice profile would identify the section, show the movement settings under test and record which configuration each player used.
