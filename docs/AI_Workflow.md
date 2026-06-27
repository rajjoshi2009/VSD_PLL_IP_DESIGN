# AI-Assisted Workflow

## Objective

Artificial Intelligence is used as an engineering assistant throughout the PLL design process. All AI-generated outputs are manually reviewed, modified where necessary, and verified through simulation.

## Workflow

1. Study the PLL building block.
2. Prepare a technical prompt.
3. Generate the initial circuit or SPICE netlist using AI.
4. Review the generated design.
5. Modify the circuit based on engineering requirements.
6. Create the schematic in xschem.
7. Simulate using ngspice.
8. Analyze waveforms and verify functionality.
9. Document observations and debugging steps.
10. Commit verified work to GitHub.

## AI Tools Used

* ChatGPT (GPT-5.5)
* OpenAI Codex (where applicable)

## Verification Policy

No AI-generated circuit is considered complete until it has been:

* Reviewed manually
* Simulated
* Compared against expected behavior
* Documented with observations

## Repository Documentation

Each PLL block will include:

* Theory
* AI Prompt
* Schematic
* SPICE Netlist
* Testbench
* Simulation Results
* Waveforms
* Observations
* Future Improvements

