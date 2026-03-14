# PWM Motor Behaviour Analysis

## Problem

Motor runs smoothly during system initialization but exhibits stepping behaviour once the system is fully loaded.

## Possible Causes

- PWM duty cycle change
- Firmware control mode switch
- Load feedback affecting control loop
- Driver current limiting

## Diagnostic Approach

1. Probe PWM signal with oscilloscope
2. Compare waveform during:
   - system boot
   - runtime operation
3. Measure duty cycle and frequency
4. Observe waveform stability

## Tools

Oscilloscope: OWON SDS1102

## Observations

Motor behaves smoothly when initialized by firmware startup sequence, suggesting the control algorithm may change during normal operation.
