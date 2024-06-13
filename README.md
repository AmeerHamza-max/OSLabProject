# OSLabProject
Process Scheduler Simulator: Implement a simulator that demonstrates various process scheduling algorithms (e.g., FCFS, SJF, Round Robin, Priority Scheduling). The simulator should allow users to input process information (arrival time, burst time, priority) and display scheduling results, including average waiting time and average turnaround time.
# Process Scheduler Simulator

This project is a GUI-based simulator for demonstrating various process scheduling algorithms such as FCFS (First-Come, First-Serve), SJF (Shortest Job First), Round Robin, and Priority Scheduling. The simulator allows users to input process information (arrival time, burst time, priority) and displays scheduling results, including average waiting time and average turnaround time.

## How to Run

1. **Install Python**: Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

2. **Install Tkinter**: Tkinter is the standard GUI toolkit for Python. It is usually included with Python, but if it's not, you can install it using the following command:
    ```sh
    pip install tk
    ```

3. **Clone the Repository**: Download or clone this repository to your local machine.
    ```sh
    git clone https://github.com/yourusername/ProcessScheduler.git
    cd ProcessScheduler
    ```

4. **Run the Application**: Execute the `process_scheduler.py` script to start the simulator.
    ```sh
    python process_scheduler.py
    ```

5. **Usage**:
   - Enter the arrival time, burst time, and priority (if applicable) for each process.
   - Select the scheduling algorithm from the dropdown menu.
   - For Round Robin, specify the time quantum.
   - Click "Add Process" to add a process to the list.
   - Click "Run Scheduler" to run the selected scheduling algorithm and display the results.

6. **Dependencies**:
    - Python 3.x
    - Tkinter (included with Python)

## Example

Here's how the GUI looks like after adding processes and running the scheduler:

!![Screenshot (69)](https://github.com/AmeerHamza-max/OSLabProject/assets/172574244/f3c81386-0855-4c24-b93c-4d9ee654989b)


