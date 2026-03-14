# PCB Power Rail Debugging Workflow

## Step 1 — Visual Inspection

- Burn marks
- Cracked capacitors
- Corrosion
- Missing components

## Step 2 — Resistance to Ground Check

Measure resistance of major rails:

- 19V
- 5V
- 3.3V

Low resistance may indicate a short.

## Step 3 — Voltage Injection

Using a bench PSU:

- Inject low voltage
- Limit current
- Identify heating component

## Step 4 — Signal Verification

Verify enable signals:

- SLP_S5
- SLP_S4
- SLP_S3
- PLTRST
