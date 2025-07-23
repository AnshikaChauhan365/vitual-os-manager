# Virtual OS Manager

The Virtual OS Manager is a GUI-based application that simulates basic operating system functions, including process management, memory allocation, and file handling. This application provides an interactive environment for users to understand and visualize fundamental OS concepts.

## Features

- **Process Management:**  
  Create and manage simulated processes with customizable properties. Start, pause, or terminate processes and observe state transitions.

- **Memory Allocation:**  
  Simulate allocation and deallocation of memory blocks to processes. Visualize memory usage and fragmentation.

- **File Handling:**  
  Perform simple file operations such as creating, reading, writing, and deleting files within a simulated file system.

- **User-Friendly GUI:**  
  Intuitive graphical user interface to interact with all OS components, making learning and demonstration easy.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries (install via pip if needed):  
  - `tkinter` (usually included with Python)
  - Any additional libraries as listed in `requirements.txt` (if present)

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/AnshikaChauhan365/vitual-os-manager.git
    cd vitual-os-manager
    ```

2. (Optional) Install required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Application

Run the main script (update the filename according to your main script, e.g., `main.py`):

```bash
python main.py
```

The GUI window will launch, and you can begin interacting with the simulated OS components.

## Project Structure

- `process/` — Code related to process management simulation
- `memory/` — Memory allocation/deallocation logic
- `filesystem/` — File handling simulation
- `gui/` — GUI components and main window logic
- `main.py` — Entry point for the application

## Usage

- **Create and manage processes** via the GUI.
- **Allocate memory** to processes and visualize the status.
- **Perform file operations** (create, read, write, delete) in the simulated environment.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Inspired by operating system textbooks and teaching materials.
- Thanks to the open-source community for libraries and tools.
