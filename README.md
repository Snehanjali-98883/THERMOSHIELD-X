# THERMOSHIELD-X

**Edge-AI Powered Hyperlocal Heat Intelligence & Autonomous Mitigation System**

## Overview

THERMOSHIELD-X is a proposed Edge-AI-powered system designed to monitor localized heat conditions, assess thermal risk, and support intelligent, resource-aware mitigation.

The project aims to move beyond generic heat alerts by combining environmental sensing, local risk assessment, predictive analysis, and feedback-based control.

## Problem Statement

Extreme heat affects people differently depending on local environmental conditions, surface heating, humidity, sunlight, and human exposure. General weather reports may not reflect the conditions experienced at a specific bus stop, rooftop, campus, or industrial location.

## Proposed Solution

THERMOSHIELD-X aims to:

- Monitor local temperature, humidity, surface heat indicators, and light intensity.
- Consider human presence and available water and energy resources.
- Assess heat risk and explore short-term heat prediction using Edge AI.
- Support appropriate mitigation actions, such as adaptive shading, ventilation, and water misting.
- Reassess conditions after an action to evaluate its effectiveness.

## System Workflow

**SENSE → ASSESS → PREDICT → DECIDE → ACT → RE-MEASURE → VERIFY**

## Technology

- **Controller:** Arduino UNO Q
- **Environmental sensing:** SHT45, MLX90614, and BH1750, as available
- **Human presence:** PIR sensor
- **Prediction:** Planned LSTM-based heat forecasting
- **Dashboard:** HTML, CSS, and JavaScript
- **Mitigation:** Servo-controlled shade, fan, and water-misting system, subject to prototype implementation

## Demonstration Scenario

A smart bus stop is the proposed demonstration site. The system evaluates local heat conditions, human presence, and resource availability before selecting a suitable response.

The architecture is intended to be adaptable to campuses, rooftops, parks, and other heat-exposed locations.

## Current Implementation Status

This repository is under development. Features should be considered implemented only when they have been built and tested. Predictive AI, hardware integration, and automated mitigation will be documented as they are verified.

## Project Team

**Team:** BYTE FORGE

**Hackathon:** BPUT Hackathon 2026

**Problem Statement:** PS02 — Heatwaves and Edge AI: Using technology to improve quality of life.

## Repository Contents

Project dashboard and supporting implementation files will be added and updated as development progresses.

