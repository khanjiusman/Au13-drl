### How to Run the Code

1. **Set Up the Environment:**
   - Install the required Conda environment using the provided YAML file:
     ```bash
     conda env create -f env_clusgym.yml
     ```

2. **Configure the Nanocluster Composition:**
   - Edit `gym_trpo_parallel.py` or `gym_trpo_single.py` to select the desired nanocluster composition.
   - **Monometallic Example:** For simulating a cluster of 13 atom gold (Au) atoms:
     ```python
     eleNames = ['Au']
     eleNums = [13]
     ```
   
3. **Run the Simulation:**
   - Execute the script using Python. Choose the appropriate version for your needs:
     ```bash
     python gym_trpo_single.py    # For single execution
     ```
