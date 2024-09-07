# Bullseye Dartboard Simulation

**Bullseye Dartboard Simulation** is a Java program that simulates a simple dartboard game where two players throw darts to score points. The program calculates scores based on the distance of the dart from the center of the dartboard, determines the winner, and handles multiple rounds of play.

## Overview

The dartboard consists of concentric rings with varying point values:
- **Bullseye**: 100 points (diameter of 6 inches)
- **First Ring**: 80 points (radius up to 3 inches)
- **Second Ring**: 60 points (radius up to 6 inches)
- **Third Ring**: 40 points (radius up to 9 inches)
- **Fourth Ring**: 20 points (radius up to 12 inches)
- **Outer Ring**: 10 points (radius up to 15 inches)

A dart lands in a specific region, and the score is determined by the closest ring boundary. Darts outside the outer ring score 0 points. If a dart lands exactly on a ring, the higher point value is awarded.

## Features

- **Score Calculation**: Computes scores based on the distance of darts from the center of the dartboard using the formula \( r^2 = x^2 + y^2 \), where \( (x, y) \) are the coordinates of the dart.
- **Player Scoring**: Handles scoring for two players, each throwing three darts per round.
- **Game Results**: Determines the winner based on scores or announces a tie.
