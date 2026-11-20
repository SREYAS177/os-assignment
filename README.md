# Operating System – Assignment 2
## OS Scheduling Visualizer

### Overview
This project is an interactive OS Scheduling Visualizer developed using Python and Google Colab. It demonstrates different CPU scheduling and disk scheduling algorithms with graphical representations and performance calculations.

The main objective is to understand how operating systems manage CPU processes and disk I/O requests using different scheduling techniques.

### Technologies Used
- Python
- Google Colab
- IPyWidgets
- Matplotlib
- Pandas

### Algorithms Implemented

#### 1. Disk Scheduling Algorithms
- FCFS (First Come First Serve)
- SSTF (Shortest Seek Time First)
- SCAN
- C-SCAN (Circular SCAN)
- LOOK

#### 2. CPU Scheduling Algorithms
- FCFS (First Come First Serve)
- SJF (Shortest Job First)
- SRTF (Shortest Remaining Time First)
- Priority Scheduling
- Round Robin

### Features
- Interactive interface for selecting scheduling algorithms.
- Customizable disk request queue and initial head position.
- Customizable CPU burst times, arrival times and priorities.
- Configurable time quantum for Round Robin scheduling.
- Calculation of total disk head movement.
- Calculation of CPU scheduling metrics:
  - Completion Time (CT)
  - Turnaround Time (TAT)
  - Waiting Time (WT)
  - Response Time (RT)
- Graphical representation of disk head movement.
- Gantt chart visualization for CPU scheduling.
- Tabular presentation of scheduling results.

### Sample Input

**Disk Scheduling**
- Disk size: 200 cylinders
- Initial head position: 50
- Request queue: 82, 170, 43, 140, 24, 16, 190

**CPU Scheduling**
- Burst times: 5, 3, 4, 2
- Arrival times: 0, 1, 2, 3
- Priority values: 2, 1, 3, 2
- Time quantum: 2

### How to Run
1. Download the `.ipynb` notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the downloaded notebook.
4. Run the cells in order.
5. Select a CPU or disk scheduling algorithm.
6. Enter the required input values.
7. Click the corresponding Run button to view the results and graphs.

### Project Structure
```text
operating-system/
│
├── Assignment-2/
│   ├── OS_Scheduling_Visualizer.ipynb
│   └── OS_Scheduling_Visualizer_Demo.mp4
│
└── README.md
```

### Learning Outcomes
- Understanding CPU scheduling techniques.
- Understanding disk scheduling techniques.
- Comparing the performance of different scheduling algorithms.
- Learning how scheduling metrics are calculated.
- Visualizing scheduling operations using Python.

### Author
**Sreyas Suresh**  
MCA Student

---

*Academic project developed as part of the Operating System coursework.*
